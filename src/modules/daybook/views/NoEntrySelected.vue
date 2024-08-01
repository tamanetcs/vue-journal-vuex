<template>
  <div class="outer">
    <div class="d-flex justify-content-center dmarc">
      <h1 class="align-self-center">No hay nada selecionado</h1>
    </div>
  </div>
  <Fab />
</template>

<script>
import { defineAsyncComponent } from 'vue'
export default {
  components:{
    Fab: defineAsyncComponent(() => import(/* webpackChunkName: 'Fab' */ '../components/Fab.vue'))
  }
}
</script>

<style lang="scss" scoped>
.outer {
  padding: 10PX; 
  background-color: gray;
  height: 100%;
}

.dmarc{
  border: 1px solid black; 
  background-color: white;
  height: 100%;
}
</style>