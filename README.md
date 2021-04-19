# Tailwind Landing page template converted to SvelteKit components

Based on the [Landing Page](https://www.tailwindtoolbox.com/templates/landing-page) template for [Tailwind CSS](https://tailwindcss.com/) created by [Tailwind Toolbox](https://www.tailwindtoolbox.com/) and converted to a [SvelteKit](https://kit.svelte.dev/) application.

![Landing Page](https://www.tailwindtoolbox.com/templates/landing-page.png)

The site is running at https://sveltekit-landing-page.vercel.app, and it is automatically deployed to [vercel](https://vercel.com) on every push using the [SvelteKit vercel adapter](https://github.com/sveltejs/kit/tree/master/packages/adapter-vercel). Check the [documentation](https://kit.svelte.dev/docs#adapters) for other adapters. 

You also have an static version available at https://sveltekit-landing-page.vercel.app/html to compare results.

## Deploying to vercel

Add `"@sveltejs/adapter-vercel"`: `"next"` to the devDependencies in your `package.json` and run `npm install`.

```shell
pnpm install -D @sveltejs/adapter-vercel
```

Then modify your svelte.config.js:

```javascript
const vercel = require('@sveltejs/adapter-vercel');
...

module.exports = {
  kit: {
    ...
    adapter: vercel()
  }
};
```

## Running locally

Clone the repo, install dependencies and start the development server:

```sh
git clone git@github.com:opensas/sveltekit-landing-page.git

cd sveltekit-landing-page

pnpm install

pnpm dev
```

The project SvelteKit project was created with

```sh
pnpm init svelte@next
```

And then tailwind support was added running:

```sh
pnpx svelte-add tailwindcss  --jit
```

And then run the project with:

```sh
pnpm dev
```

Check the [svelte-add/tailwindcss](https://github.com/svelte-add/tailwindcss) github repo for more info.

# create-svelte
 
Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte);

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm init svelte@next

# create a new project in my-app
npm init svelte@next my-app
```

> Note: the `@next` is temporary

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

Before creating a production version of your app, install an [adapter](https://kit.svelte.dev/docs#adapters) for your target environment. Then:

```bash
npm run build
```

> You can preview the built app with `npm start`, regardless of whether you installed an adapter. This should _not_ be used to serve your app in production.
