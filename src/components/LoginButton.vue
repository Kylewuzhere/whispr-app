<template>
  <div>
    <button class="text-gray-200 bg-neutral-600 h-14 rounded-xl px-4 hover:bg-neutral-700 hover:text-white active:scale-95 transition" @click="login">Log in with Auth0</button>
  </div>
</template>
<script lang="ts">
  import { useAuth0 } from '@auth0/auth0-vue';

  export default {
    setup() {
      const { loginWithRedirect } = useAuth0();

      return {
        login: () => {
          loginWithRedirect();
        } 
      };
    }
  };
</script>