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
<div class="one" v-if="Age < 18">Подросток</div>
<div class="one" v-else-if="19 < Age && age < 25">Молодой человек</div>
<div class="one" v-else="Age > 26">Мужчина</div>
</template>

<style scoped>
</style>
