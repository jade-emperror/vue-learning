<template>
  <div id="app">
    <div>
    <h1>{{ usr_name }}</h1>
    <span>{{ role }}</span>
  </div>
  <p>
    {{ msg }} <b>{{ org }}</b>
  </p>
    <img alt="Vue logo" src="./assets/logo.png">
  </div>
</template>

<script>
export default {
  // component options
  data(){
    return{
      usr_name:'Bharath',
      role:'Trainee Software Engineer',
      org:'RecruitCRM',
      msg:"Hope you are doing good at ",
    }
  }
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
