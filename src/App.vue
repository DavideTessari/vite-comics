<script>
import AppHeader from './components/AppHeader.vue';
import AppProductsList from './components/AppProductsList.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppHeader,
    AppProductsList,
    AppFooter
  }
}
</script>

<template>
  <AppHeader>ciao ciao</AppHeader>

  <main>
    <AppProductsList>ciao ciao</AppProductsList>
  </main>

  <AppFooter></AppFooter>
</template>

<style lang="scss">
@use './style/generic';
</style>