<template>
  <form>
    <div class="form-group">
      <label>Username</label>
      <input class="form-control" placeholder="Enter your name" required />
    </div>
    <div class="form-group">
      <label>Password</label>
      <input class="form-control" type="password" placeholder="password" required />
    </div>
    <router-link to="/HomePage">Login</router-link>
  </form>
</template>

<script lang="ts">

import { defineComponent } from 'vue';

export default defineComponent({
  name: 'LoginForm',
  props: {
    Username: String,
    Password: String,
  },
});

</script>


<style scoped>

</style>
