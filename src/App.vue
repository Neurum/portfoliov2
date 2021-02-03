<template>
  <div class="container">
    <Nav />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Nav from './components/Nav';
import Main from './components/Main.vue';
import Footer from './components/Footer';

export default {
  name: 'App',
  components: {
    Nav,
    Main,
    Footer,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  background-color: #2f2f2f;
  color: lightgray;
  font-family: 'Muli', serif;
  font-weight: 700;
}

html {
  font-size: 62.5%;
}

.container {
  margin: 3rem 20rem;
  height: calc(100vh - 8rem);
}
</style>
