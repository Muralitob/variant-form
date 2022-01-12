<template>
  <div id="app">
    <VFormDesigner ref="vfDesignerRef"></VFormDesigner>
  </div>
</template>

<script>
import VFormDesigner from './components/form-designer/index.vue'
//添加注释
//添加注释2
export default {
  name: 'App',
  components: {
    VFormDesigner,
  }
}
</script>

<style lang="scss">
  #app {
    height: 100%;
  }
</style>
