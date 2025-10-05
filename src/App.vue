<script setup>
import FeatureCard from './components/FeatureCard.vue';
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <!-- <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" /> -->

    <div class="wrapper">
    </div>
  </header>
  
  <div>
    <HelloWorld msg="You did it!" />
    <!-- <TheWelcome /> -->
    <FeatureCard die="your twingcle" />
  </div>
</template>

<style scoped>

</style>
