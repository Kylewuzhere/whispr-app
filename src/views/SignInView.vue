<template>
  <div class="flex flex-col justify-center items-center bg-neutral-800 text-white mt-20 p-4 rounded-xl h-[20rem] w-[25rem] shadow-[0_7px_30px_0px_rgba(255,255,255,0.3)]
  ">
    <form class="">
      <div>
        <h1 class="text-4xl mb-4 text-center font-black font-dancing">Whispr</h1>

      </div>
      <button class="bg-neutral-600 h-12 rounded-xl px-4">Sign in with Google <font-awesome-icon :icon="['fab', 'google']" /></button>
    </form>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap');

.font-dancing {
  font-family: 'Dancing Script', cursive;
}
</style>
