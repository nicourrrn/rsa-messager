<template>
  <button
    @click="props.handleClick"
    class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded"
  >
    Click me
  </button>
</template>

<script setup>
const props = defineProps(["handleClick"]);
</script>
