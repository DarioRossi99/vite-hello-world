<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
import AppEasterEgg from './components/AppEasterEgg.vue'

export default{
  components:{AppTitle,AppHero,AppEasterEgg}
}

</script>

<template>
  <AppTitle></AppTitle>
  <AppHero></AppHero>
  <AppEasterEgg></AppEasterEgg>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
