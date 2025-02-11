<script setup>
const content = ref('before')
</script>

<template>
  <div>
    <ChildComponent @update-content="content = $event"/>
    {{ content }}
  </div>
</template>
