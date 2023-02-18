<script>
export default{
data(){
  return{
    order: '',
    visible: false,
    visible1: false,
    visible2: false,
  }
},
methods: {
one(){
      this.visible = true;
},
  two() {
    this.visible1 = true;
  },
  three() {
    this.visible2 = true;
  }
}
}
</script>

<template>
<div class="one">
<p>Хто ты?</p>
<input name="radio" type="radio" v-model="order" value="Хто я" @click="one">
<label for="">?</label>
<br>
<input name="radio" type="radio" v-model="order" value="Розбiйнiк" @click="two">
<label for="">?</label>
<br>
<input name="radio" type="radio" v-model="order" value="Выйди розбiйнiк" @click="three">
<label for="">?</label>
</div>

<p> Ваш выбор: {{ order }}</p>
<br>
</template>

<style scoped>
</style>
