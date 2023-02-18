<script>
export default{
data(){
  return{
  what: ' ',
  }
},
methods: {
}
}
</script>

<template>
<input class="one" v-model="what" v-on:keyup.enter="submit">
<p>{{ what }}</p>
<a href="#" v-on:keyup.ctrl="sub">...</a>
</template>

<style scoped>
</style>
 
