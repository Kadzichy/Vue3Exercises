<script>
export default {
    emits: ['show', 'show1'],
    data() {
        return {
        }
    },
    methods: {
        handle() {
            this.$emit('show');
        },
        handle1() {
            this.$emit('show1');
        },
    }
}
</script>

<template>
<button class="button" @click="handle">Oleg</button>
<button class="button" @click="handle1">Tinkoff</button>
</template>
