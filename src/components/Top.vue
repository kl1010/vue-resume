<template>
  <header  id = "header" class="w3-container w3-border-bottom w3-bottombar w3-border-red">
    <div class = "w3-third">
      <img src="../assets/img/logo.png">
    </div>
    <div class="w3-third">
      <img id = "img-kapil" class = "w3-circle" src="../assets/img/kapil.jpeg">
      <h3>Full Stack Developer at <span> Capital Signs</span></h3>
      <h4>
        <span class = "w3-padding"> <i class="fa fa-map-marker" aria-hidden="true"></i> Atlanta, GA </span>
        <span class = "w3-padding"><i class="fa fa-envelope" aria-hidden="true"></i> kapil@kapil.cc </span>
      </h4>
    </div>
    <div class="w3-third w3-right-align">
      <h1 class = "" id = "name"> KAPIL LAMICHHANE</h1>
      <h3 class = "" id = "position"> FULL STACK DEVELOPER</h3>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Top'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#img-kapil{
max-width:150px;
}
#header{
background-image : url(../assets/img/header.png);
background-repeat:repeat-x;
width:100%;
}

</style>
