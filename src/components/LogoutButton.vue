<template>
  <div>
    <button class="dark:text-green-500 hover:text-green-500 dark:hover:text-green-400 transition" @click="logout">Log out</button>
  </div>
</template>
<script lang="ts">
  import { useAuth0 } from '@auth0/auth0-vue';

  export default {
    setup() {
      const { logout } = useAuth0();

      return {
        logout: () => {
          logout({ logoutParams: { returnTo: window.location.origin } });
        }
      };
    }
  };
</script>