<script>
export default{
data(){
  return{
    hidden1: true,
    hidden2: false,
  }
},
}
</script>

<template>
<div class="one" v-if="hidden1">Oleg</div>
<div class="one" v-if="!hidden2">Tinkoff</div>

</template>

<style scoped>
</style>
