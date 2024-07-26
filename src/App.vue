<script>
import AppHero from './components/AppHero.vue'
import AppTitle from './components/AppTitle.vue'

export default{
  components:{
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <header>
    <AppTitle />
  </header>
  
  <main>
    <AppHero />
  </main>
</template>

<style scoped>

</style>
