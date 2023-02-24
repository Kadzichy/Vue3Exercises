<script>
import User from './components/Employee.vue'
export default {
  data() {
    return {
      users: [
        {
          id: 1,
          name: 'Oleg',
          salary: 1000,
          age: 18
        },
        {
          id: 2,
          name: 'Oleg',
          salary: 2000,
          age: 15
        },
      ],
    }
  },
  components: {
    User
  }
}
</script>

<template>
<User v-for="User in users" :name="User.name" :salary="User.salary" :age="User.age" :key="User.id" />
</template>

<style scoped>
</style>
