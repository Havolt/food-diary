<template>
  <div id="app">
    <header class="fd-nav">
      <div class="fd-nav__title">Food Diary</div>
      <div class="fd-nav__links">
        <router-link class="fd-nav__links__link" to="/">Home</router-link> 
        <router-link class="fd-nav__links__link" to="/about">About</router-link>
      </div>
    </header>
    <router-view/>
  </div>
</template>

<script>



</script>

<style lang="scss">

* {
  padding: 0;
  margin: 0;
  border: 0;
}

body, html {
  font-family: Arial, Helvetica, sans-serif;
}

body {
  font-size: 62.5%;
}

a {
  text-decoration: none;
}

.fd-nav {
  border-bottom: 1px solid #123752;
  display: flex;
  align-items: center;
  background-color: #29526D;
  color: rgb(245, 245, 245);
}

.fd-nav__title {
  font-size: 1.8rem;
  flex: 1;
  
  padding: .2em 1em;
}

.fd-nav__links {
  display: flex;
  
  flex: 1;
  
}

.fd-nav__links__link {
  padding: 0 .8rem;
  color: rgb(230, 230, 230);
  font-size: 1.3rem;
  transform: scale(1);
  transition: transform ease-in .3s;
}

.fd-nav__links__link:hover {
  transition: transform ease-in .3s;
  transform: scale(1.2);
  color: white;
}

@keyframes fd-nav-pulse {
  0% {}
}

</style>
