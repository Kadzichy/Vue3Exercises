<script>
export default{
data(){
  return{
    obj: {User:'100$', User1:'200$', User2:'300$'},
  }
},
methods: {
}
}
</script>

<template>
  <ul class="one">
    <li v-for="elem in obj">{{ elem }}</li>
  </ul>
  <ul class="one">
    <li v-for="(key, elem) in obj"> {{ elem }} - {{ key }}</li>
  </ul>
  <ul class="one">
    <li v-for="(key, elem, index) in obj"> {{ elem }} - {{ key }} - {{ index }}</li>
  </ul>
  <ul class="one">
    <li v-for="(key, elem, index) in obj"> {{ elem }} - {{ key }} - {{ index+1 }}</li>
  </ul>
</template>

<style scoped>
</style>
