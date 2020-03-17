<template>
  <div class="hello">
   <app-deneme></app-deneme>
   <app-home></app-home>
   <app-head></app-head>
  </div>
</template>

<script>
import Deneme from "@/components/Deneme"
import Home from "@/components/Home"
import Head from "@/components/Head"
export default {
 components:{
   appHome:Home,
   appDeneme:Deneme,
   appHead:Head
 }
}
</script>

<style scoped>

</style>
