<script>
export default{
data(){
  return{
    text: 'one hargreaves',
  }
},
methods: 
{
  change: function(){
    this.text = 'Who?';
},
change2: function(){
  this.text = 'Where?'
}
}
}
</script>

<template>
<p class="one">{{ text }}</p>
<button class="button" @click="change">Some text 1</button>
<button class="button" @click="change2">Some text 2</button>
</template>

<style scoped>
</style>
