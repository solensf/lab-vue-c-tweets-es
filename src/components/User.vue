<script setup>
const props = defineProps({
  user: String,
});
</script>

<template>
  <span class="user">
    <span class="name">{{ props.user.name }}</span>
    <span class="handle">@{{ props.user.handle }}</span>
  </span>
</template>
<style></style>
