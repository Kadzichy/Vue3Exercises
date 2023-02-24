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
    remove(id) {
      this.Users = this.Users.filter((User) => {
        return User.id !== id;
      })
    }
  } 
}
</script>
<template>
<User v-for   ="User in Users"
		:id     ="User.id"
		:name   ="User.name"
		:surn   ="User.surn"
		@remove ="remove"
		:key    ="User.id"/>
</template>

<style scoped>
</style>
