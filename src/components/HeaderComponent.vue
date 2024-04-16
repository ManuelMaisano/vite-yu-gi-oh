<template>
    <div class="d-flex align-items-center bg-white">
        <img id="logo" class="img-fluid"
            src="https://upload.wikimedia.org/wikipedia/commons/1/11/Yu-Gi-Oh%21_%28Logo%29.jpg" alt="Logo">
        <h1>Yu-Gi-Oh Api</h1>
    </div>
</template>

<script>
export default {
    name: 'HeaderComponent'
}
</script>


<style lang="scss" scoped>
#logo {
    width: 200px;
    padding: 20px;

}

h1 {
    font-weight: 400;
    font-size: 55px;

}
</style>