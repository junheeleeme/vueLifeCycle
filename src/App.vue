<template>  
  <div>
    <h1>Vue Life-Cycle</h1>
    
  </div>
</template>

<script>

export default {
  name: 'App',
  beforeCreate(){
    console.log('Before Created');
  },
  created(){
    console.log('Created');
  },
  beforeMount(){
    console.log('BeforeMount');
  },
  mounted(){
    console.log('Mounted!');
  },
  beforeUpdate(){
    console.log('Before Update!');
  },
  updated(){
    console.log('updated!');
  },
  beforeUnmount() {
    console.log('Before UnMounted!');
  },
  unmounted() {
    console.log('UnMounted!');
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
