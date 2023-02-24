<script>
export default {
    props: ['name'],
    data() {
        return {
        }
    }
}
</script>

<template>
<ul class="one">
    <li v-for="Oleg in name">{{ Oleg }}</li>
</ul>
</template>
