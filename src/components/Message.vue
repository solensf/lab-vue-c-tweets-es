<script setup>
const props = defineProps({
  message: String,
});
</script>

<template>

    <p class="message"> {{ props.message }} </p>

</template>
<style></style>
