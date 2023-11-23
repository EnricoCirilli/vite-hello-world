<template lang="">
    <h1 class="text-danger">{{ text }}</h1>
</template>
<script>
export default {
    data() {
        return {
            text: 'Header'
        }
    }
}
</script>
<style scoped>
    h1 {
        color: seagreen;
    }
</style>