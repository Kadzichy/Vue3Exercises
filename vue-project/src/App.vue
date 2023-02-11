<script>
export default{
data(){
  return{
    products: [
      {
        id: 1,
        name: 'product1',
      },
      {
        id: 2,
        name: 'product2',
      },
      {
        id: 3,
        name: 'product3',
      },
    ]
  }
},
methods: {
}
}
</script>

<template>
<ul class='one'>
  <div v-for="product in products" :key='products.id'>{{ prod.name }} </div>
  </ul>
</template>

<style scoped>
</style>
