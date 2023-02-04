<script>
export default{
data(){
  return{
  }
},
methods: {
  show: function(str){
  alert(str*str);
  },
  show1: function(str1){
    alert(str1*str1)
  }
}
}
</script>

<template>
<button class="button" @click="show(2)">2^2</button>
<button class="button" @click="show1(3)">3^2</button>
</template>

<style scoped>
</style>
