<script>
</script>

<template>
  <nav class="navbar">
      <a href="/">Home</a>
      <a href="#projects">projects</a>
      <a href="#contact">Contact</a>
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
  position: sticky;
  top: 0;
  background-color: #f03f35;

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

.container {
  padding: 50px;
  border-left: 2px solid rgba(18, 18, 18, 0.136);
  border-right: 2px solid rgba(18, 18, 18, 0.136);
  min-height: 500px;
  margin: 0 20vh;
}

.container a:hover {
  color: #ff0d00;
  font-size: 1.1rem;
}

</style>
