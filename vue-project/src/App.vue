<script>
export default{
data(){
  return{
  }
},
methods: {
}
}
</script>

<template>
  <p class="one">1+1=?</p>
    <select class="one" v-model="number">
      <option>2</option>
      <option>-0</option>
      <option>512</option>
    </select>
    <p>{{ number }}</p>
</template>

<style scoped>
</style>
