<template>
  <div id="app">
    <Vhead></Vhead>
    <Vnav></Vnav>
    <Vslide></Vslide>
    <Home></Home>
  </div>
</template>

<script>
import Home from './components/Home'
import Vhead from './components/Vhead'
import Vnav from './components/Vnav'
import Vslide from './components/Vslide'
export default {
  name: 'app',
  components: {
    Home,Vhead,Vnav,Vslide
  }
}
</script>

<style>
*{
  padding:0px;
  margin:0px;
  font-family: "Helvetica Neue",Helvetica,Arial,"Microsoft Yahei",STHeiti,sans-serif;
}
body{
  background-color: rgba(0,0,0,0.02)
}
</style>
