<template>
  <header>
    <h1>GraphCMS Starter blog</h1>
    <nav>
      <router-link exact to="/" class="link">Home</router-link>
      <router-link to="/about" class="link">About</router-link>
    </nav>
  </header>
</template>
​
<script>
  export default {
    name: 'AppHeader'
  }
</script>