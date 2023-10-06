<template>
  <div class="container" id="main">
    <div class="main" >
      <div id="text">
        <h1>Axel Holberg <br> Ferrufino Arze</h1>  
      </div>
      <div id="photo">
        <a href="https://www.instagram.com/p/CknfZ8RN15o/?utm_source=ig_web_copy_link" target="_blank"><img src="/pic.png" alt="photo" ></a>
      </div>
    </div>
  </div>
  <div class="container" id="projects">
      <div class="projects">
          <h1>Things i did</h1>
          <ul>
              <li><a href="https://axel0203.github.io/cube/">- Cube</a></li>
              <li><a href="https://axel0203.github.io/cubes/">- Cubes!</a></li>
              <li><a href="https://axel0203.github.io/space-game/">- Three.js game</a></li>
              <li><a href="https://axel0203.github.io/myRoom/">- Three.js portfolio</a></li>
          </ul>   
      </div>
  </div>
  <div class="container" id="contact">
      <div class="contact">
          <h1>CONTACT</h1>
          <div class="tabs">
              <div class="mail">
                  <h2>MAIL</h2>
                  <a href="mailto:arze.fer03@gmail.com" target="_blank">arze.fer03@gmail.com</a>
              </div>
              <div class="social">
                  <h2>SOCIAL MEDIAS</h2>
                  <ul>
                      <li><a target="_blank" href="https://www.linkedin.com/in/axel-ferrufino/">linkedin</a></li>
                      <li><a target="_blank" href="https://www.instagram.com/axel._.fer/">instagram</a></li>
                  </ul>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
</script>

<style>
.main #text {
  color: #f03f35;
  text-align: left;
  margin: auto;
  flex: 1;
}

.main #photo {
  flex: 1;
}

@media (min-width: 700px) {
  .main {
    display: flex;
  }
}

@media (max-width: 700px) {
  .about #text p {
    text-align: justify;
  }
}

.main #photo img {
  max-width: 100%;
}

.projects {
  -webkit-text-fill-color: #f03f35;
  text-align: left;
}
.projects .tabs div {
  margin-top: 25px;
}
.projects a {
  text-decoration: none;
  color: #f03f35;
}

.projects ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.projects ul li {
  margin: 3px;
  font-family: "Montserrat", sans-serif;
  font-weight: 900;
}

.contact {
  -webkit-text-fill-color: #f03f35;
  text-align: left;
}
.contact .tabs div {
  margin-top: 25px;
}
.contact a {
  text-decoration: none;
  color: #f03f35;
}

.contact ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.contact ul li {
  margin: 3px;
}
</style>
