<script setup>
const props = defineProps({
  msg: String
})
</script>

<template>
  <div>
    <h1 class="text-green-600 text-lg">{{ msg }}</h1>
  </div>
</template>
