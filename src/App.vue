<template>
 
<head>
  <title>Save a Tree</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
  <script defer src="https://cdn.jsdelivr.net/npm/jquery@3.6.4/dist/jquery.slim.min.js"></script>
  <script defer src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script defer src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
</head>
  <div class="vh-100" id="app">
    <Comp1 />
    <img class="img-fluid" alt="beautiful tree" src="https://tse3.mm.bing.net/th?id=OIP.37pAteYwW-ju4CxyAlCIcgHaEn&pid=Api&P=0https://tse3.mm.bing.net/th?id=OIP.37pAteYwW-ju4CxyAlCIcgHaEn&pid=Api&P=0"/>
    <Comp2 />
    <Comp3 />
    <Comp4 />

  </div>
</template>

<script>
import Comp1 from './components/Comp1.vue'
import Comp2 from './components/Comp2.vue'
import Comp3 from './components/Comp3.vue'
import Comp4 from './components/Comp4.vue'


export default {
  name: 'App',
  components: {
    Comp1,
    Comp2,
    Comp3,
    Comp4
  }
}
</script>

<style>
#app {
  text-align: center;
}
</style>
