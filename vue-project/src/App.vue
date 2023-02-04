<script>
export default{
data(){
  return{
    cost: '1',
    amount: '2',
  }
},
computed: {
  price: function(){
    return this.cost * this.amount;
  }
},
methods: {
change: function(){
  this.cost = '3'
}
}
}
</script>

<template>
<p class="one">{{ cost }}</p>
<p class="one">{{ amount }}</p>
<p class="one">{{ price }}</p>
<button class="button" @click="change">cost</button>
</template>

<style scoped>
</style>
