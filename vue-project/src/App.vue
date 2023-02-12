<script>
export default{
data(){
  return{
    hunters: ['Oleg', 'tinkoff'],
  }
},
methods: {
add: function(){
  this.hunters.push('Oleg');
},
del: function(){
  this.hunters.shift();
},
}
}
</script>

<template>
<ul class="styled">
  <li v-for="elem in hunters">{{ elem }}</li>
</ul>
<button class="button" @click="add">add</button>
<br>
<button class="button" @click="del">delete</button>
</template>

<style scoped>
</style>
