<script setup>
const content = ref('before')
//const content = useState(() => 'before')
</script>

<template>
  <div>
    <ChildComponent @update-content="content = $event"/>
    {{ content }}
  </div>
</template>
