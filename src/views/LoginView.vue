<script setup lang="ts">
import LoginButton from '../components/LoginButton.vue'

</script>

<template>
  <div class="flex flex-col justify-center items-center mt-20 p-4 border-2 rounded w-96 h-[20rem] max-w-[90%] bg-neutral-300 text-gray-950 border-green-500 dark:bg-neutral-800 dark:text-white dark:border-green-900 ">
    <form class="sm:m-10">
      <div>
        <h1 class="text-6xl mb-12 text-center font-black font-dancing hover:scale-110 text-green-700 hover:text-green-500 dark:hover:text-green-400 dark:text-green-500 transition">Whispr</h1>

      </div>
      <button class="text-gray-200 bg-neutral-600 h-14 rounded-xl px-4 hover:bg-neutral-700 hover:text-white active:scale-95 transition">Sign in with Google <font-awesome-icon :icon="['fab', 'google']" />
        
      </button>
      <LoginButton/>
    </form>
  </div>
</template>



<style>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap');

.font-dancing {
  font-family: 'Dancing Script', cursive;
}

</style>
