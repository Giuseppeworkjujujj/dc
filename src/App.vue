<template>
 <div id="app">
  <HelloWorld/>
 <header1/>
 </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import header1 from './components/header1.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    header1,
  },
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
