<script>
export default{
data(){
  return{
    cssClass: 'Oleg',
  }
},
methods: {
}
}
</script>

<template>
<p :class="cssClass">Oleg Tinkoff</p>
</template>

<style scoped>
p{color:red}
</style>
