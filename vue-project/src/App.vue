<script>
export default{
data(){
  return{
    newNumber: '',
    Numbers: ['1', '2', '3', '4', '5'],
  }
},
methods: {
  RemoveNumber: function (index) {
    this.Numbers.splice(index, 1);
  }
}
}
</script>

<template>
<ul class="styled">
  <li v-for="(Number, index) in 
			Numbers" :key="index">
    {{ Number }}
    <br>
    <button class="button" @click="RemoveNumber(index)">Remove</button>
  </li>
</ul>
</template>
<style scoped>
</style>
