<script>
export default{
data(){
  return{
    dayOfWeek: 'Понедельник',
    options: ['Понедельник', 'Вторник','Среда', 'Четверг', 'Пятница','Суббота', 'Воскресенье'], 
    day: '1',
    options1: ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10', '11', '12', '13', '14', '15', '16', '17', '18', '19', '20', '21', '22', '23', '24', '25', '26', '27', '28', '29', '30',' 31'],
    month: 'Январь',
    options2: ['Январь', 'Февраль','Март', 'Апрель', 'Май','Июнь', 'Июль', 'Август', 'Сентябрь','Октябрь', 'Ноябрь', 'Декабрь'],
    year: '2023',
    options3: ['2023', '2022','2021', '2020', '2019','2018', '2017', '2016']
  }
},
methods: {
}
}
</script>

<template>
    <select class="hunter" v-model="dayOfWeek">
      <option v-for="option in options">{{ option }}</option>
    </select>
<select class="hunter" v-model="day">
  <option v-for="option1 in options1">{{ option1 }}</option>
</select>
<select class="hunter" v-model="month">
  <option v-for="option2 in options2">{{ option2 }}</option>
</select>
<select class="hunter" v-model="year">
  <option v-for="option3 in options3">{{ option3 }}</option>
</select>
</template>

<style scoped>
</style>
