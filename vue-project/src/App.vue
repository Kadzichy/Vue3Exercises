<script>
import Oleg from './components/Employee.vue'
export default {
  data() {
    return {
      
    }
  },
  components: {
    Oleg
  },
  methods: {
    Oleg() {
      alert('1, 2, 3, 4');
    },
    tinkoff(){
      alert('1, 2, 3, 4')
    }
  }
}
</script>

<template>
<Oleg @show="Oleg" @show1="Tinkoff" />
</template>


<style scoped>
</style>
