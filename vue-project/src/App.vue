<script>
import Oleg from './components/Employee.vue'
export default {
  components: {
    Oleg
  }
}
</script>

<template>
<Oleg :name="['Oleg', 'Oleg', 'Oleg', 'Oleg']"/>
</template>

<style scoped>
</style>
