<script>
export default{
data(){
  return{
    items: [1, 2, 3, 4, 5],
  }
},
methods: {
}
}
</script>

<template>
  <div class="one" v-for="elem in items">{{ elem }}</div>
  <div class="one" v-for="elem in items">{{ elem*elem }}</div>
  <ul class="one" v-for="elem in items">{{ elem }}</ul>
</template>

<style scoped>
</style>
