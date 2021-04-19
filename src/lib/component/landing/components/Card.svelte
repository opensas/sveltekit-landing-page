<script lang="ts">
	import Button from './Button.svelte';
</script>

<div class="w-full md:w-1/3 p-6 flex flex-col flex-grow flex-shrink">
  <div class="flex-1 bg-white rounded-t rounded-b-none overflow-hidden shadow">
    <!-- svelte-ignore a11y-invalid-attribute -->
    <a href="#" class="flex flex-wrap no-underline hover:no-underline">
      <p class="w-full text-gray-600 text-xs md:text-sm px-6">xGETTING STARTED</p>
      <div class="w-full font-bold text-xl text-gray-800 px-6">Lorem ipsum dolor sit amet.</div>
      <p class="text-gray-800 text-base px-6 mb-5">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam at ipsum eu nunc
        commodo posuere et sit amet ligula.
      </p>
    </a>
  </div>
  <div class="flex-none mt-auto bg-white rounded-b rounded-t-none overflow-hidden shadow p-6">
    <Button secondary>Action2</Button>
  </div>
</div>