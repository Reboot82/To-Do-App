<template>
  <div id="app">
    <div class="container">
      <td-header></td-header>
    </div>
    <div class="container">
      <td-home></td-home>
    </div>
    <div class="container">
      <td-footer></td-footer>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Home from './components/Home.vue'

export default {
  components: {
    tdHeader: Header,
    tdFooter: Footer,
    tdHome: Home
  }
}
</script>

<style>

</style>
