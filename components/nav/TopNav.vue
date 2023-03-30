<template>
  <div class="nav">

    <div class="left-nav" style="display: flex;">
      <h2><NuxtLink to="/">Strona domowa</NuxtLink></h2>
    </div>

    <div class="left-nav" style="display: flex;">
      <h2><NuxtLink to="/gallery">Galeria</NuxtLink></h2>
    </div>

  </div>
</template>

<script>

</script>
<style scoped>
  .nav {
    display: flex;
    /* flex-direction: column; */
    border: 3px solid black;
    background-color: blue;
    height: 100%;
    width: 100%;
    max-height: 70px;
    min-height: 70px;
    max-width: calc(100vw - 200px);
    min-width: 200px;
    margin-inline: 50px;
    padding-inline: 50px;
    margin-bottom: 20px;
    justify-content: center;
  }

  .left-nav {
    border: 1px solid black;
    background-color: rgb(255, 255, 255, 0.9);
    justify-content: center;
    padding-inline: 20px;
    padding-top: 10px;
    padding-bottom: 10px;
    max-height: 70px;
    min-height: 70px;
    max-width: 300px;
    min-width: 150px;
  }
</style>
