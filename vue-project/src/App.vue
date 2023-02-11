<script>
export default{
data(){
  return{
    day: 'Вторник',
  }
},
methods: {
}
}
</script>

<template>
<div class="one" v-if="day === 'Понедельник'">Понедельник</div>
<div class="one" v-if="day === 'Вторник'">Вторник</div>
<div class="one" v-if="day === 'Среда'">Среда</div>
<div class="one" v-if="day === 'Четверг'">Четверг</div>
<div class="one" v-if="day === 'Пятница'">Пятница</div>
<div class="one" v-if="day === 'Суббота'">Суббота</div>
<div class="one" v-if="day === 'Воскресенье'">Воскресенье</div>
</template>

<style scoped>
</style>
