<script>
export default{
data(){
  return{
    two: ' ',
    // Oleg: ' ',
  }
},
methods: {
list: function(){
  }
}
}
</script>

<template>
<textarea class="text-field__input" v-model="two"></textarea>
<p class="one">{{ two }}</p>
<ul>
  <li v-for="three in two">{{ three }}</li>
</ul>
</template>

<style scoped>
</style>
