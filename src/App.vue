<template>
  <router-view/>
  <bottom-menu>
    
  </bottom-menu>
</template>
<script>
import BottomMenu from './components/BottomMenu.vue';

export default {
  components: {BottomMenu},
}

</script>

<style lang="scss">
body {
  margin: 0;
  padding-bottom: 100px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
