<template>
  <nav>
    <router-link class="nav-links" to="/">Home</router-link> ||
    <router-link class="nav-link" to="/personal_info">Personal Info</router-link> ||
    <router-link class="nav-link" to="/education">Education & Skills</router-link> ||
    <router-link class="nav-link" to="/projects">Projects</router-link> ||
    <router-link class="nav-link" to="/testimonials">Testimonials</router-link> ||
    <router-link class="nav-link" to="/contact">Contact</router-link> ||
    <router-link class="nav-link" to="/about">About</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: 'Helvelow', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
@import url('https://fonts.cdnfonts.com/css/helvelow');

nav {
  padding: 30px;
}

nav a {
  font-weight: 900;
  color: #204960;
  text-decoration: none;
  font-size: 20px;
}

.nav-links:hover {
  transform: scale(1.4);
  transition: ease-in 8s alternate;
}

nav a.router-link-exact-active {
  color: #42b983;
}

</style>
