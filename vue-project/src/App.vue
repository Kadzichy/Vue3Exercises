<script>
export default{
data(){
  return{
    hidden: true,
  }
},
methods: {
hide: function(){
  this.hidden = false;
}
}
}
</script>

<template>
  <button class="button" @click="hide">hide</button> 
  <div v-if="hidden">
  <div class="one">Oleg</div>
  <div class="one">Tinkoff</div>
  <div class="one">Bank</div>
  </div>
</template>

<style scoped>
</style>
