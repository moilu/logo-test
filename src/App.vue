<template>
  <div id="app">
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/main/Header.vue'
import Main from './components/main/Main.vue'
import Footer from './components/main/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style>
:root {
  --main-bg-color: #FF7315;
  --secondary-bg-color: #faf4f2;
  --light-color  : #F9F9F9;
  --dark-color   : #222222;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  background-color: var(--secondary-bg-color);
  display: flex;
      justify-content: center;
  font-family: 'Poppins', 'Open Sans', 'sans-serif';
  height: 100vh;
  margin: 0;
  overflow: auto;
}

#app {

  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
