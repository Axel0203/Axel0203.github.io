<script>
</script>

<template>
  <nav class="navbar">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/contact">Contact</RouterLink>
        <RouterLink to="/projects">projects</RouterLink>
  </nav>
  <RouterView />
</template>

<style >

* {
  font-family: "Work Sans", sans-serif;
  font-weight: 600;
  background-color: #b7e3e4;
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
  text-align: center;
  margin-bottom: 20px;
  margin-top: 20px;
}
.navbar a:link,
.navbar a:visited {
  background-color: #f03f35;
  color: white;
  padding: 14px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}
.navbar a:hover,
.navbar a:active {
  background-color: red;
}

#container {
  width: 66%;
  padding: 50px;
  border: 2px solid rgba(18, 18, 18, 0.136);
  min-height: 500px;
  margin: auto;
}

#container a:hover {
  color: #ff0d00;
  font-size: 1.1rem;
}

</style>
