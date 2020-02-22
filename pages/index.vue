<template>
  <div class="container">
    <Logo />
    <Header />
    <nuxt-link to="/users">Users</nuxt-link>
    <nuxt-link to="/products">Products Page</nuxt-link>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
</script>

<style>
</style>
