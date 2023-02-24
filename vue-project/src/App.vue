<script>
import Oleg from './components/Employee.vue'
export default {
  data() {
    return {
      name: 'Oleg',
      surn: 'Tinkoff',
    }
  },
  components: {
    Oleg
  }
}
</script>

<template>
<Oleg :name="name" :surn="surn"/>
</template>


<style scoped>
</style>
