<template>
  <div class="headers">
    <nav>
      <router-link to="/" exact>Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>|
      <router-link to="/form">Forms</router-link>
    </nav>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style lang="scss" scoped>
.headers {
  background: #000;
  color: #fff;
}
</style>
