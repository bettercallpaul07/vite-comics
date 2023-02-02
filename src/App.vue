<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppLinks from "./components/AppLinks.vue";
import AppFooter from "./components/AppFooter.vue";



export default {
  name: "App",
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    AppLinks
  }
};
</script>

<template>

  <AppHeader />

  <AppMain />

  <AppLinks />

  <AppFooter />



</template>


<style lang="scss">
@import "./styles/main.scss"
</style>
