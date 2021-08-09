<template>
  <div class="natureItemCardContainer">
    <NatureItemCard title="Snakes"/>
    <NatureItemCard title="Lizards"/>
    <NatureItemCard title="Frogs"/>
    <NatureItemCard title="Spiders"/>
    <NatureItemCard title="Birds"/>
    <NatureItemCard title="Plants"/>
  </div>
</template>

<script>
import NatureItemCard from '@/components/NatureItemCard.vue'

export default {
  name: 'NatureItemCardContainer',
  props: {
    title: String
  },
  components: {
    NatureItemCard
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.natureItemCardContainer {
  display: flex;
  flex-wrap: wrap;
  color: #42b983;
  border: black solid 2px;
  width: 40%;
  margin: auto;
}
</style>
