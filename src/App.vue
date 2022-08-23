<template>
  <div id="app">
   <MyHero />
   <MyTitle />
   
  </div>
</template>

<script>
import MyHero from '@/components/MyHero.vue';
import MyTitle from '@/components/MyTitle.vue';

export default {
  name: 'App',
  components: {
    MyHero,
    MyTitle,
    
  }
}
</script>

<style lang="scss">
  #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  font-size: 40px;
}
</style>
