<script>
import User from './components/Employee.vue'
export default {
  data() {
    return {
      
    }
  },
  components: {
    User
  },
  methods: {
    UserName(name) {
      console.log(name);
    },
    UserSalary(name, salary){
console.log(name, salary);
    }
  }
}
</script>

<template>
<User @show="UserName" @show1="UserSalary"/>
</template>


<style scoped>
</style>
