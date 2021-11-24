<template>
  <div id="app">
    <Header />

    <Main />

    <Footer />
  </div>
</template>

<script>
// import componets from component folder
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

// App general styles  
<style lang="scss">
// import font styles (Oswald | weight : 400 & 600)
@import url('https://fonts.googleapis.com/css2?family=Oswald:wght@400;600&display=swap');

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

#app {
  // font-family: Avenir, Helvetica, Arial, sans-serif;
  font-family: 'Oswald', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
