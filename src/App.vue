<script>

// 1 - Import il file in cima al mio script e gli assegno un nome
import AppTitle from './components/AppTitle.vue';

export default {
  // 2 - Lo inserisco nella lista dei componenti
  components: {
    AppTitle,
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

    <main>
      
    </main>
    
  </div>
</template>

<style scoped>
</style>
