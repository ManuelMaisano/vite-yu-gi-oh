<template>
  <div class="card" style="width: 18rem;">
    <img class="card-img-top" :src="image" :alt="name">
    <div class="card-body">
      <p class="card-text text-center info">
        <span>{{ name }}</span>
        <br>
        <span>{{ archetype }}</span>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardComponent',
  props: [
    'id',
    'image',
    'name',
    'archetype'
  ],
}
</script>

<style lang="scss" scoped>
.info {
  background-color: #D48F38;
  display: flex;
  flex-direction: column;
  justify-content: space-between;

}
</style>