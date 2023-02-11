<script>
export default{
data(){
  return{
    arr: [1, -2, 3, -4, 5],
  }
},
methods: {
}
}
</script>

<template>
  <ul class="one">
    <template v-for="elem in arr">
    <li v-if="elem > 0 ">{{ elem }}</li>
    </template>
  </ul>
</template>

<style scoped>
</style>
