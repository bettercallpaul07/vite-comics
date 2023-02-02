<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFooter from "./components/AppFooter.vue";



export default {
  name: "App",
  componets: {
    AppHeader,
    AppMain,
    AppFooter,
  }
}


</script>

<template>

  <AppHeader />



</template>


<style lang="scss">
@import "./styles/main.scss"
</style>
