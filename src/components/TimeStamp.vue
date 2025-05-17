<script setup>
const props = defineProps({
  timestamp: String,
});
</script>

<template>
 
    <span class="timestamp"> {{ props.timestamp }}    </span>

</template>
<style></style>