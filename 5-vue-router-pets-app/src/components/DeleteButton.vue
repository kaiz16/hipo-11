<!-- child of Pet.vue -->
<template>
<!-- Clicking on this button will emit an event to it's parent (Pet.vue) -->
  <button v-on:click="$emit('delete')">Delete</button>
</template>

<script>
export default {

}
</script>

<style>

</style>