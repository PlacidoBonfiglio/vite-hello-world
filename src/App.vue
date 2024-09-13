<script>

// 1 - Import il file in cima al mio script e gli assegno un nome
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  // 2 - Lo inserisco nella lista dei componenti
  components: {
    AppTitle,
    AppHero,
  },

  data () {
    return {

    }
  }
}

</script>

<template>
  <div>
    <header>
      <AppTitle/>
    </header>

    <AppHero/>
    
  </div>
</template>

<style scoped>
</style>
