<script>
export default {
    emits: ['show', 'show1'],
    data() {
        return {
        }
    },
    methods: {
        handleName() {
            this.$emit('show', 'Oleg',);
        },
        handleSalary(){
            this.$emit('show1', 'Tinkoff', '20000');
        }
    }
}
</script>

<template>
<button class="button" @click="handleName">Oleg</button>
<button class="button" @click="handleSalary">tinkoff</button>
</template>
