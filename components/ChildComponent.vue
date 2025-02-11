<script setup>
await useFetch('https://google.com')
const emit = defineEmits(['updateContent'])
emit('updateContent', "after")
</script>

<template>
  <h2>ChildComponent</h2>
</template>
