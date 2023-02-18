<script>
export default{
data(){
  return{
    visible: true,
    styles: {
      hidden: true,
    },
  }
},
methods: {
setDone:function(){
  this.styles.hidden = false;
},
setTwo: function(){
  this.styles.hidden = true;
},
  toggle: function () {
    this.visible = !this.visible;
  }
}
}
</script>

<template>
<button class="button" @click="toggle">toggle</button>
<p class="hunter" v-if="visible">Oleg</p>
<p :class="styles">Tinkoff</p>
<button class="button" @click="setDone">visible</button>
<button class="button" @click="setTwo">hide</button>
</template>

<style scoped>
p.hidden{
  display: none;
}
p{color:red};
</style>
