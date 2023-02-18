<script>
export default{
data(){
  return{
    isValid: true,
    isDisabled: true,
  }
},
methods: {
}
}
</script>

<template>
<p :class="{valid: isValid, disable: isDisabled}">Oleg</p>
</template>

<style scoped>
p{color:red};
</style>
