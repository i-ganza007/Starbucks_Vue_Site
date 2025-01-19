<template>
  <NavBar/>
  <FirstSection/>
  <SecondSection/>
  <ThirdSection/>
</template>

<script>
import NavBar from './components/NavBar.vue';
import FirstSection from './components/FirstSection.vue';
import SecondSection from './components/SecondSection.vue';
import ThirdSection from './components/ThirdSection.vue';


export default {
  name: 'App',
  components: {
    NavBar,
    FirstSection,
    SecondSection,
    ThirdSection,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
