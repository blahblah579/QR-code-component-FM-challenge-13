<template>
  <v-app>
    <v-main class="main d-flex align-center">
      <HomePage />
    </v-main>
  </v-app>
</template>

<script setup>
import HomePage from "./components/HomePage.vue";
</script>

<style scoped>
.main {
  background-color: hsl(212, 45%, 89%);
}
</style>