<script>
export default{
data(){
  return{
    isAdmin: false,
  }
},
methods: {
}
}
</script>

<template>
<div class="one" v-if="isAdmin">Oleg tinkoff</div>
<div class="one" v-else>Oleg Gazmanov</div>
</template>

<style scoped>
</style>
