<script>
export default{
data(){
  return{
    New: '',
    anythings: ['1', '2', '3', '4'],
  }
},
methods: {
  Add: function () {
    this.anythings.unshift(this.New);
  }
}
}
</script>

<template>
<ul class="styled">
  <li v-for="(anything, index) in 
			anythings" :key="index">
    {{ anything }}
  </li>
</ul>
<input  v-model="New">
<br>
<button class="button" @click="Add">add</button>
</template>

<style scoped>
</style>
