<script setup>
const props = defineProps({
  Actions: Array,
});
</script>

<template>
  <div class="actions">
    <i 
    v-for="(icon, index) in props.actions"
    :key="index"
    :class="icon"
    ></i>
  </div>
</template>

<style scoped></style>
