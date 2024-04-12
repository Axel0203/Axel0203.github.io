<script>
export default {
  data() {
    return {
    }
  },
  methods: {
    
  }
}
</script>

<template>
  <nav class="navbar">
        <RouterLink  to="/">Home</RouterLink>
        <RouterLink   to="/contact">Contact</RouterLink>
        <RouterLink   to="/projects">Projects</RouterLink>
  </nav>
  
  <!--
    <RouterView />

    <router-view v-slot="{Component}">
    <transition>
      <Component :is="Component" />
    </transition>
  </router-view>
  -->

  <router-view v-slot="{Component}">
    <transition name="slide-down" mode="out-in">
      <Component :is="Component" />
    </transition>
  </router-view>
</template>

<style >

body {
  background-color: #b7e3e4;
}

* {
  font-family: "Work Sans", sans-serif;
  font-weight: 600;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Montserrat", sans-serif;
  font-weight: 900;
}
.navbar {
  background-color: #f03f35;
  text-align: center;
  padding-top: 5px;
}

.navbar a:hover{
  text-shadow: 0px 0px 2px #ffffff;
}

#container {
  width: 66%;
  padding: 50px;
  min-height: 500px;
  margin: auto;
}

#container a:hover {
  text-shadow: 0px 0px 2px #ffffff;
}

.navbar .router-link-active {
  background-color: #b7e3e4;
  color: #f03f35;
  padding: 14px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  border-top-right-radius: 1rem;
  border-top-left-radius: 1rem;
}

.navbar a {
  background-color: #f03f35;
  color: white;
  padding: 14px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

.slide-down-enter-from,
.slide-down-leave-to {
  opacity: 0;
  transform: translateY(100px);
}

.slide-down-enter-active,
.slide-down-leave-active {
  transition: 0.3s ease-out;
}

</style>
