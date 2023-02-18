<script>
export default{
data(){
  return{
    res: 0,
    sum: 0,
    num: 0,
    num1: 0, 
    num2: 0,
  }
},
methods: {
  calc: function () {
    this.res = Math.sqrt(this.num);
  },
  summary:function(){
    this.sum = this.num1 + this.num2;
  }
}
}
</script>

<template>
<p class="one">{{ res }}</p>
<input class="text-field__input" v-model="num">
<button class="button" @click="calc">Sqrt</button>
<p class="one">{{ sum }}</p>
<input class="text-field__input" v-model=num1>
<input class="text-field__input" v-model=num2>
<button class="button" @click="summary">Sum</button>

</template>

<style scoped>
</style>
