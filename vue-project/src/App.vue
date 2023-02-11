<script>
export default{
data(){
  return{
    arr: ['x', 'y', 'z'],
  }
},
methods: {
}
}
</script>

<template>
  <ul class="one" v-for="(key, elem) in arr"> {{ key }} {{ elem }}</ul>
</template>

<style scoped>
</style>
