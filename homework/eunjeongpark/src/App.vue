<template>
  <div id="app">
    <router-view></router-view>
    <Footer></Footer>
  </div>
</template>

<script>
import Footer from './components/Footer';

export default {
  name: 'App',
  components: {
    Footer
  }
}
</script>

<style>

</style>
