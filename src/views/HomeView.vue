<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <h1>Hola Mundo</h1>
    <button @click="goToDayBook" class="btn btn-primary">Primary</button>
    <button @click="goToDayBook" class="btn btn-primary">Secundary</button>
    <button @click="goToDayBook" class="btn btn-success">Success</button>

  </div>
</template>

<script>
  export default{
    methods:{
      goToDayBook(){
        this.$router.push({name:'no-entry'})
      }
    }
  }
</script>
