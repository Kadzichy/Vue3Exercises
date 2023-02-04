<script>
export default{
data(){
  return{
    num1: 1,
    num2: 2,
    text: 'Sum'
  }
},
methods: {
  show: function(){
    let text = this.cape(this.text)
    alert(this.num1 + this.num2);
  },
  cape: function(str){
    return str[0].toUpperCase() + str.slice(1);
  }
}
}
</script>

<template>
<a class="inline-link-3" href="https://www.youtube.com/" onclick="event.preventDefault()">Link</a>
<button class="button" @click.once="show">click</button>
</template>

<style scoped>
</style>
