<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <div class="greetings">
    <!-- <h1 class="green bg-blue-500 text-4xl">{{ msg }}</h1> -->
    <h3 class="text-3xl font-bold underline">
      You’ve successfully created a project with
    </h3>
  </div>
</template>

<style scoped>

</style>
