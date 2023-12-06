<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="bg-neutral-900 min-h-screen">
    <header class=" top-1 h-12 w-full">
      <div>
        <nav class="text-white">
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/about">About</RouterLink>
          <RouterLink to="/sign-in">Sign In</RouterLink>
        </nav>
      </div>
    </header>

    <div class="flex justify-center items-center">
      <RouterView />
    </div>
  </div>
</template>

<style scoped>
</style>
