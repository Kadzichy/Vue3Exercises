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
<div class="one" v-if="visible">Oleg</div>
<button class="button" @click="toggle2">you</button>
<div class="one" v-if="visible2">Tinkoff</div>
<button class="button" @click="toggle3">say</button>
<div class="one" v-if="visible3">Bank</div>


</template>

<style scoped>
</style>
