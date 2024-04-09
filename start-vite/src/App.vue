<script>
export default{
  data(){
    return{
      message: 'La mia prima app con vite'
    }
  }
}
</script>

<template>
  <div id="AppTitle">
    <h1 class="center">
    {{ message }}
  </h1>
  </div>
  <div id="AppHero">
    <img src="../public/vi.jpg" alt="">
  </div>
 
</template>

<style>
.center{
  text-align: center;
}
</style>
