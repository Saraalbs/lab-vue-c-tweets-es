<script setup>
const props = defineProps({
  user: Object,
});
</script>

<template span class="user">
  <span class="name">{{ props.user.name }}</span>
  <span class="handle">@ {{ props.user.handle }} </span>
</template>

<style scoped></style>
