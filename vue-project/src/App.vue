<script>
export default{
data(){
  return{
    visible1: true,
    visible2: false,
  }
},
}
</script>

<template>
<div class="one" v-if="visible1">Oleg</div>
<div class="one" v-if="!visible2">Tinkoff</div>

</template>

<style scoped>
</style>
