<script>
import Card1Component from './Card1Component.vue'
import Card2Component from './Card2Component.vue'
import Card3Component from './Card3Component.vue'
import Card4Component from './Card4Component.vue'
import Card5Component from './Card5Component.vue'
import Card6Component from './Card6Component.vue'
export default {
  name: 'Main',
  data() {
    return {

    }
  },
  components: {
    Card1Component,
    Card2Component,
    Card3Component,
    Card4Component,
    Card5Component,
    Card6Component,
  }
}
</script>

<template>
  <main>
    <div class="container">
      <!-- UNICA RIGA DEL LAYOUT -->
      <div class="row">
        <Card1Component></Card1Component>
        <Card2Component></Card2Component>
        <Card3Component></Card3Component>
        <Card4Component></Card4Component>
        <Card5Component></Card5Component>
        <Card6Component></Card6Component>
      </div>
    </div>
  </main>
</template>

<style lang="scss"></style>