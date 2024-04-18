<template>
    <div>
        <main class="container bg-white">
            
            <CardList />
        </main>

    </div>
</template>

<script>
import CardList from './MainComponent/CardList.vue'
    export default {
        name: 'MainComponent',
        components:{
            CardList
        }
        
    }
</script>

<style lang="scss" scoped>
main{
    margin: 80px auto;
}
</style>