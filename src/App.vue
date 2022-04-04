<template>
  <div id="app">
    <HeaderAvada></HeaderAvada>
    <MainAvada></MainAvada>
    <MainSezA></MainSezA>
    <MainSezB></MainSezB>
    <MainSezC></MainSezC>
    <MainSezD></MainSezD>
    <MainSezE></MainSezE>
  </div>
</template>

<script>
import HeaderAvada from './components/HeaderAvada.vue'
import MainAvada from './components/MainAvada.vue'
import MainSezA from './components/MainSezA.vue'
import MainSezB from './components/MainSezB.vue'
import MainSezC from './components/MainSezC.vue'
import MainSezD from './components/MainSezD.vue'
import MainSezE from './components/MainSezE.vue'
export default {
  name: 'App',
  components: {
    HeaderAvada,
    MainAvada,
    MainSezA,
    MainSezB,
    MainSezC,
    MainSezD,
    MainSezE
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'DM Sans', sans-serif;
}

// $primary: rgb(139, 139, 139);
@import "~bootstrap/scss/bootstrap";
</style>
