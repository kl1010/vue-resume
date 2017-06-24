<template>
  <div id="app">
    <top></top>
    <middle></middle>
    <MidBottom></MidBottom>
    <bottom></bottom>
    <FootBottom></FootBottom>
  </div>
</template>

<script>
import Top from './components/Top'
import Middle from './components/Middle'
import MidBottom from './components/MidBottom'
import Bottom from './components/Bottom'
import FootBottom from './components/FootBottom'

export default {
  name: 'app',
  components: {
    Top,
    Middle,
    MidBottom,
    Bottom,
    FootBottom
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
@@import "./assets/css/kp.css"
</style>
