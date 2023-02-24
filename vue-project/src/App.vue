<script>
export default{
data(){
  return{
    mens: [
      {
        id: 1,
        name: 'Oleg Sverskiy',
        salary: 100,
        age: 15,
      },
      {
        id: 2,
        name: 'Oleg Gazmanov',
        salary: 200,
        age: 15,
      },
      {
        id: 3,
        name: 'Oleg Tinkoff',
        salary: 300,
        age: 16,
      },
    ],
  }
},
methods: {
  removemen: function (id) {
    this.mens = this.mens.filter((men) => {
      return men.id !== id;
    })
  }
}
}
</script>

<template>
<table class="one">
  <tr v-for="men in mens" :key="men.id"> {{ men.name }} {{ men.salary }} {{ men.age }} <button class="button" @click="removemen(mens.id)">Remove</button>
</tr>
</table>
</template>
<style scoped>
</style>
