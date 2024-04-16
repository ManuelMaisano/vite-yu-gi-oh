<template>
  <HeaderComponent />
</template>

<script>
import { store } from './store';
import HeaderComponent from './components/HeaderComponent.vue';
  export default {
    name: 'App',
    data(){
      return{
        store
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>