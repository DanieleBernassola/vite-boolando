<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";
import MainComponent from "./components/MainComponent.vue";
export default {
  name: 'myApp',
  data() {
    return {

    }
  },
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent,
  }
}
</script>

<template>
  <HeaderComponent></HeaderComponent>
  <MainComponent></MainComponent>
  <FooterComponent></FooterComponent>
</template>

<style lang="scss">
@use '../src/assets/styles/main.scss'
</style>
