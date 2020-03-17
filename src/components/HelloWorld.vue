<template>
  <div class="hello">
   <app-deneme></app-deneme>
   <app-home></app-home>
  </div>
</template>

<script>
import Deneme from "@/components/Deneme"
import Home from "@/components/Home"
export default {
 components:{
   appHome:Home
 }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
