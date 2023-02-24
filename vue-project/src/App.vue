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
  }
}
</script>

<template>
<User @show="UserName"/>
</template>

<style scoped>
</style>
