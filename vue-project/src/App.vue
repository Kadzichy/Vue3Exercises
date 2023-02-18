<script>
export default{
data(){
  return{
   
    isDisabled1: true,
    checked: false,
  }
},
methods: {
 
  toggle1: function () {
    this.isDisabled1 = false;
  },
}
}
</script>

<template>

<button class="button" @click="toggle">btn</button>
<input type="text" class="one" placeholder="one" v-bind:disabled="isDisabled1">
<input type="checkbox" v-model="checked" @click="toggle1">
</template>

<style scoped>
</style>
