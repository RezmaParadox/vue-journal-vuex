<template>
  <div class="d-flex justify-content-center">
    <h1 class="align-self-center">No hay nada seleccionado</h1>
    <Fab/>
  </div>
</template>

<script>
import { defineAsyncComponent } from 'vue'
export default {
  components:{
    Fab: defineAsyncComponent (() => import('../components/Fab.vue'))
  }
}
</script>

<style lang="scss" scoped>
div{
    height: 100%;
}
</style>