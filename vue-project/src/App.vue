<script>
export default{
data(){
  
},
methods: {
  show: function(){
    alert(new Date().toLocaleDateString());
  }
}
}
</script>

<template>
<button class="button" v-on:mouseover="show">Data</button>
</template>

<style scoped>
</style>
