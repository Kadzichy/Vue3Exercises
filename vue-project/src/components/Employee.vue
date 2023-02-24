<script>
export default {
    props: ['name', 'surn', 'salary'],
    data() {
        return {
        }
    }
}
</script>

<template>
<p class="one">
{{ name }} 
{{ surn }}
{{ salary }} 
</p>
</template>
