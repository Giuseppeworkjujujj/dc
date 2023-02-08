<template>
  <div>
  <pippo v-for="(immagine, index) in immagini" :key="index" :immagine="immagine"/>
  </div>
</template>

<script>
import Fumetti from '@/data/Fumetti.js'
import pippo from '@/components/pippo.vue'
export default {
  name: 'HelloWorld',
  components: {
    pippo,
  },
  data(){
    return{
      immagini:  Fumetti.filmLinks
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div{
  height: 200px;
}
</style>
