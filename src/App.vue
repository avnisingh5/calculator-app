<template>
  <h1>Calculator</h1>
  <div>
    <input type="number" v-model.number="firstNum"/>+
    <input type="number" v-model.number="secondNum"/>=
    <span>{{firstNum + secondNum}}

    </span>
  </div>
  
</template>

<script>


export default {
  name: 'App',
  data(){
    return{
      firstNum:"",
      secondNum:""
    }
  }
 
 
  
};
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
