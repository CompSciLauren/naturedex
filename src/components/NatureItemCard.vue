<template>
  <div class="natureItemCard">
      <h1>{{title}}</h1>
  </div>
</template>

<script>
export default {
  name: 'NatureItemCard',
  props: {
    title: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
    font-size: 28px;
}

.natureItemCard {
  color: #42b983;
  border: #43b983 solid 2px;
  width: 50%;
}
</style>
