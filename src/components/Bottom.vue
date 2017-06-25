<template>
  <section class="w3-container">
    <div class="w3-panel w3-red">
      <h3>Recent Work</h3>
    </div>

    <div class="w3-quarter">
      <figure>
        <img src="../assets/img/ncc.jpg" class = "kp-img" alt="National Championship">
        <figcaption>National Championship Countdown for Atlanta Airport</figcaption>
    </figure>
    </div>
    <div class="w3-quarter">
      <figure>
        <img src="../assets/img/north.png" class = "kp-img" alt="Wait times Data">
        <figcaption>Wait times Data for Atlanta Airport</figcaption>
    </figure>
    </div>
    <div class="w3-quarter">
      <figure>
        <img src="../assets/img/tv-ui.png" class = "kp-img" alt="TV UI">
        <figcaption>Tv UI for Capital Signs</figcaption>
    </figure>
    </div>
    <div class="w3-quarter">
      <figure>
        <img src="../assets/img/kpi.png" class = "kp-img" alt="KPI">
        <figcaption>KPI for VanKirk Electric</figcaption>
    </figure>
    </div>
  </section>

</template>

<script>
export default {
  name: 'Bottom'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.kp-img{
width:100%;
max-width:300px;
max-height:150px
}
</style>
