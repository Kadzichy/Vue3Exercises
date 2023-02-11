<script>
export default{
data(){
  return{
    Age: 15,
  }
},
methods: {
}
}
</script>

<template>
<p class="one" v-if="Age < 18">Подросток</p>
<p class="one" v-else-if="19 < Age && age < 25">Молодой человек</p>
<p class="one" v-else="Age > 26">Мужчина</p>
</template>

<style scoped>
</style>
