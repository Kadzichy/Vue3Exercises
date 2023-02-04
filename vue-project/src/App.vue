<script>
export default{
data(){
  return{
    arr: ['x', 'y', 'z'],
    arr1: [1, 2, 3],
  }
}
}
</script>

<template>
<div class="one">{{ arr[0] }}</div>
<div class="one">{{ arr[1] }}</div>
<div class="one">{{ arr[2] }}</div>
<div class="one">{{ arr1[0] + arr1[1] + arr1[2] }}</div>
</template>

<style scoped>
</style>
