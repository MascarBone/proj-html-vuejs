<template>
  <div id="app">
    <Header class="mb-3" />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
  }
}
</script>

<style lang="scss">
@import '~bootstrap/scss/bootstrap';
@import '~@fortawesome/fontawesome-free/css/all.css';
@import './style/variables.scss';

.my_btn-primary {
  background-color: $amaranth;
  color: $white;
  font-weight: bold;
  text-transform: uppercase;
  border: none;
  border-radius: 50px;
  padding: 15px 20px;
}
.my_btn-primary:hover {
  background-color: #46c197;
}
</style>
