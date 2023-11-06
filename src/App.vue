<script>
import HelloWorld from './components/HelloWorld.vue';
import AppHero from './components/AppHero.vue';
import Header from './components/Header.vue';

export default {
  
  components: {
        HelloWorld,
        AppHero,
        Header,
      }

  
}
</script>

<template>
<Header/>
  <!-- <h1>{{ message }}</h1> -->
 <AppHero/>
  <!-- <HelloWorld msg="Vite + Vue" /> -->
</template>

