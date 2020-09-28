<template>
  <div class="container">
    <p>{{ message }}</p>
    <router-link to="/price">Price Page</router-link>
    <router-link to="/mypage">My Page</router-link>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      message: 'Hello World!!'
    }
  }
}
</script>

<style>
</style>
