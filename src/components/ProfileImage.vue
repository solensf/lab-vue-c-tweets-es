<script setup>
const props = defineProps({
  image: String,

});
 
</script>


<template>
<img :src="props.image"
      class="profile"
      alt="profile"
    />
</template>

<style></style>