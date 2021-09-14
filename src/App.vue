<template>
<Header></Header>
<Main></Main>
<Footer></Footer>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

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

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  font-size: 65%;
}

body {
  overflow: hidden;
  font-family: Arial, sans-serif;
  font-size: 1.6rem;
}

a {
  text-decoration: none;
  padding: 0 3px;
}

ul {
  list-style-type: none;
}

</style>
