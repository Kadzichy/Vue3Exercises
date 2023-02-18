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
<input type="text" class="text-field__input" placeholder="one" v-bind:disabled="isDisabled1">
<br>
<input type="checkbox" v-model="checked" @click="toggle1">
<!-- <button class="button" @click="toggle">Button</button> -->
</template>

<style scoped>
</style>
