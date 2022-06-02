<template>
  <MainTimer/>
</template>

<script>
import MainTimer from './components/main-timer.vue'

export default {
  name: 'App',
  components: {
    MainTimer,
}
}
</script>

<style>
#app {
  background-image: url("./assets/background.jpg");
  width:100%;	
  height:100%;
  position:fixed;
  background-size:100% 100%;
}
</style>
