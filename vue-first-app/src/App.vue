<template>
  <div id="app">
    <!-- todo -->
    <!-- header -->
    <Header :msg="'abcd'"></Header>
    <!-- contents -->

    <!-- footer -->
  </div>
</template>

<script>
import Header from './components/header.vue';
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
//    HelloWorld
      Header
  }
}
</script>

