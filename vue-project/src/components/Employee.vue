<script>
export default {
    props: ['name', 'surn', 'age'],
    data() {
        return {
        }
    }
}
</script>

<template>
  <p class="one">{{ name }}</p>
  <p class="one">{{ surn }}</p>
  <p class="one">{{ age }}</p>
</template>
