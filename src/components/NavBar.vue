<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/products">Products</router-link>
    <router-link to="/admin">Admin</router-link>
    <router-link to="/contact">Contact</router-link>
  </nav>
</template>

<script>
    export default {
        name: 'NavBar'
    }
</script>

<style scoped>
nav {
    background-color: #EB455F;
}
</style>