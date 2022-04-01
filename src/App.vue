<template>
  <div id="app">
    <HeaderAvada></HeaderAvada>
  </div>
</template>

<script>
import HeaderAvada from './components/HeaderAvada.vue'
export default {
  name: 'App',
  components: {
    HeaderAvada
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

// $primary: rgb(139, 139, 139);

@import "~bootstrap/scss/bootstrap";
</style>
