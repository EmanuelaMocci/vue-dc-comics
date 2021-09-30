<template>
  <div id="app">
    <Header/>
    <Hero/>
    <main>
       <componenteMain1/>
       <componenteMain2/>
    </main>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import componenteMain1 from './components/ComponenteMain1.vue';
import componenteMain2 from './components/ComponenteMain2.vue';
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Hero,
    componenteMain1,
    componenteMain2,
    Footer
  }
}
</script>

<style lang="scss">
#app{
  font-family: 'PT Sans Narrow', sans-serif;
}
</style>
