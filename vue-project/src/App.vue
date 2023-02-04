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
  <button @click="show" class="button"> Date 
  </button>
</template>

<style scoped>
</style>
