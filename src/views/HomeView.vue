<template>
  <div id="container">
        <div class="main">
            <div id="text">
                <h1>Axel Holberg <br> Ferrufino Arze</h1>  
            </div>
            <div id="photo">
                <a href="https://www.instagram.com/p/CknfZ8RN15o/?utm_source=ig_web_copy_link" target="_blank"><img src="/pic.png" alt="photo" ></a>
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

</style>
