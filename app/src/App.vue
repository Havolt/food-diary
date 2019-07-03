<template>
  <div id="app">
    <header class="fd-nav">
      <div class="fd-nav-title">Food Diary</div>
      <div class="fd-nav-links">
        <router-link to="/">Home</router-link> 
        <router-link to="/about">About</router-link>
      </div>
    </header>
    <router-view/>
  </div>
</template>

<script>



</script>

<style lang="scss">

body, html {
  font-family: Arial, Helvetica, sans-serif;
}

a {
  text-decoration: none;
  color: black;
}

</style>
