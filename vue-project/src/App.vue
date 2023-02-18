<script>
export default{
data(){
  return{
    lang: [],
  }
},
methods: {
}
}
</script>

<template>
<div class="one">
<input class="one" type="checkbox" v-model="lang" value="Oleg">
<label>1</label>
<br>
<input class="one" type="checkbox" v-model="lang" value="Tinkoff">
<label>2</label>
<ol>
<li v-for="elem in lang">{{ elem }}</li>
</ol>
</div>

</template>

<style scoped>
</style>
