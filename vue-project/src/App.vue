<script>
import User from './components/Employee.vue'
export default {
  data() {
    return {
      Users: [
        {
          id: 1,
          name: 'Oleg',
          surn: 'Tinkoff'
        },
        {
          id: 2,
          name: 'Oleg',
          surn: 'Tinkoff'
        },
        {
          id: 3,
          name: 'Oleg',
          surn: 'Tinkoff'
        },
      ],
    }
  },
  components: {
    User
  },
  methods: {
    add(name, surn){
      let id = this.Users.length + 1;
      this.Users.push({
        id, name, surn
      });
    }
  }
}
</script>

<template>
<User @add="add"/>
</template>


<style scoped>
</style>
