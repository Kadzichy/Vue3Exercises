<script>
export default{
data(){
  return{
    obj: {
      done: true,
      selected: false,
    },
  }
},
methods: {
}
}
</script>

<template>
<p :class="selected">Oleg</p>
<p :class="obj">Tinkoff</p>
</template>

<style scoped>
p{color:red}
</style>
