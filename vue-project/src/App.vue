<script>
export default{
data(){
  return{
    mens: [
      {
        id: 1,
        name: 'Oleg tinkoff',
        salary: 100,
        age: 10,
      },
      {
        id: 2,
        name: 'Oleg tinkoff',
        salary: 200,
        age: 15,
      },
      {
        id: 3,
        name: 'Oleg tinkoff',
        salary: 300,
        age: 16,
      },
    ]
  }
},
methods: {
  edit(men) {
    men.isEdit = true;
  },
  save(men) {
    men.isEdit = false;
  },
}
}

</script>
<template>
<table class="men">
<tr v-for="men in mens" :key="men.id"> 
<template v-if="!men.isEdit">
  {{ men.name }} {{ men.salary }} {{ men.age }}<button class="button" @click="edit(men)">edit</button>
</template>
<template v-else>
  <input v-model="men.name">
  <input v-model="men.salary">
  <input v-model="men.age">
  <button class="button" @click="save(men)">
      save
  </button>
</template>
</tr>
</table>
</template>

<style scoped>
</style>
