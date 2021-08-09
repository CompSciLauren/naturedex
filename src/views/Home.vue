<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld appTitle="Naturedex"/>
    <NatureItemCardContainer/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import NatureItemCardContainer from '@/components/NatureItemCardContainer.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    NatureItemCardContainer
  }
}
</script>
