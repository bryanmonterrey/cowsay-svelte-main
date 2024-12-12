<script lang="ts">
  export let text: string = "";
</script>

<div>
  <p class="text-[#DDDDDD] mb-1">Enter text</p>
  <input
    class="w-full border-none p-2 text-left text-black bg-white rounded-lg shadow-md focus:border-red-500 focus:ring-red-500 placeholder:text-black"
    type="text"
    placeholder="Ex: Hello, world!"
    bind:value={text}
  />
</div>
