<template>
<div>
  <h1>App Component</h1>
  <input type="text" placeholder="say sumn" v-model="msg">
  <Products :greeting="msg"/>
  <Products greeting="class 1"/>
</div>
</template>

<script>
import Products from './components/Products.vue';



export default {
  name: 'App',
  data(){
    return{
       msg: ''
    }
  },
  components: {Products
  },
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
