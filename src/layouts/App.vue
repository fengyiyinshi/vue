<template>
  <div id="app">
    <!-- <loading/> -->
    <Header/>
    <router-view></router-view>
    <Footer/>
  </div>
</template>

<script>
  
import Header from './Header.vue';
import Footer from './Footer.vue';
import loading from '../components/loading.vue';

export default {
  name: 'App',
  components: {
    Header,Footer,loading
  }
}
</script>

<style>

</style>
