<template>
  <div class="container">
    <p>Hello Nuxt.js!</p>
    <p>{{ message }}</p>
    <hr>
    <router-link to="/price">Price Page</router-link>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      message: "Hello World"
    };
  }
};
</script>

<style>
</style>
