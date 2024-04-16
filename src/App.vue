<template>
 <h1 class="text-center">{{ store.prova }}</h1>
</template>

<script>
import { store } from './store';
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