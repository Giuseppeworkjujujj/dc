<template>
  <div class="container-fluid">
  <div class="row-1">
    <img class="logo-1" src="../assets/dc-logo.png" alt="">
    <ul class="one">
      <li>CHARACTERS</li>
      <li>COMICS</li>
      <li>MOVIES</li>
      <li>TV</li>
      <li>GAMES</li>
      <li>VIDEOS</li>
      <li>FANS</li>
    </ul>
  </div>
</div>
</template>

<script>

export default {
  name: 'HeaderSito',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang='scss' scoped>
  .container-fluid{
    height: 100px;
    background-color: #265ee9;
    width: 100%;
    margin-left: 0px;
    img{
      height: 50px;
    }
    .one{
      list-style: none;
      height: 100px;
      li{
        color: white;
      }
    }
  }
</style>
