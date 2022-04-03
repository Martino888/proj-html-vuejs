<template>
  <div id="app">
    <HeaderAvada></HeaderAvada>
    <MainAvada></MainAvada>
    <MainSezA></MainSezA>
  </div>
</template>

<script>
import HeaderAvada from './components/HeaderAvada.vue'
import MainAvada from './components/MainAvada.vue'
import MainSezA from './components/MainSezA.vue'
export default {
  name: 'App',
  components: {
    HeaderAvada,
    MainAvada,
    MainSezA
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
