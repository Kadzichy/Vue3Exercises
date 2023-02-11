<script>
export default{
data(){
  return{
    visible: true,
    visible2: true,
    visible3: true,
  }
},
methods: {
  toggle: function(){
    this.visible = !this.visible;
  },
  toggle2: function () {
    this.visible2 = !this.visible2;
  },
  toggle3: function () {
    this.visible3 = !this.visible3;
  }
}
}
</script>

<template>
<button class="button" @click="toggle">What</button>
<div class="one">{{visible ? 'Oleg' : 'tinkoff'}}</div>
<button class="button" @click="toggle2">you</button>
<div class="one">{{visible2 ? 'Yes' : 'No'}}</div>
<button class="button" @click="toggle3">say</button>
<div class="one" >{{visible3 ? 'Oleg' : 'Gazmanov'}}</div>


</template>

<style scoped>
</style>
