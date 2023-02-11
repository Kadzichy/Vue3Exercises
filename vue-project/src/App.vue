<script>
export default{
data(){
  return{
    isAuth: true,
  }
},
methods: {
toggle: function(){
  this.isAuth = false;
}
}
}
</script>

<template>
  <button class="button" @click="toggle">Oleg</button>
  <p class="one" v-show="isAuth">Oleg Tinkoff</p>
</template>

<style scoped>
</style>
