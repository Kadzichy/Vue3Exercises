<script>
export default{
data(){
  return{
    visible: true,
btnHide: true,
btnVis: false,
  }
},
methods: {
  hide: function(){
    this.visible = false;
    this.btnHide = false;
    this.btnVis = true;
  },
  vis: function(){
    this.visible = true;
    this.btnHide = true;
    this.btnVis = false;
  }
}
}
</script>

<template>
<div class="one" v-if="hidden1">Oleg</div>
<div class="one" v-if="!hidden2">Tinkoff</div>
<button class="button" @click="hide" v-if="btnHide">hide</button>
<button class="button" @click="vis" v-if="btnVis">visible</button>

</template>

<style scoped>
</style>
