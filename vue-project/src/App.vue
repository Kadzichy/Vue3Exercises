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
<p class="one" v-if="day === 'Понедельник'">Понедельник</p>
<p class="one" v-if="day === 'Вторник'">Вторник</p>
<p class="one" v-if="day === 'Среда'">Среда</p>
<p class="one" v-if="day === 'Четверг'">Четверг</p>
<p class="one" v-if="day === 'Пятница'">Пятница</p>
<p class="one" v-if="day === 'Суббота'">Суббота</p>
<p class="one" v-if="day === 'Воскресенье'">Воскресенье</p>
</template>

<style scoped>
</style>
