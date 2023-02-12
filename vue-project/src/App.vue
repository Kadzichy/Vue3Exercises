<script>
export default{
data(){
  return{
    a: ['Oleg', 'tinkoff'],
  }
},
methods: {
add: function(){
  this.a.push('Oleg');
},
del: function(){
  this.a.shift();
},
}
}
</script>

<template>
<ul class="styled">
  <li v-for="elem in a">{{ elem }}</li>
</ul>
<button class="button" @click="add">add</button>
<br>
<button class="button" @click="del">delete</button>
</template>

<style scoped>
</style>
