<script>
export default {
    data() {
        return {
            message: ''
        }
    },
    methods: {
        greetMessage() {
            this.message = 'Hello Vue Options'
        }
    },
    created() {
        this.greetMessage()
    }
}
</script>

<template>
    <div>{{ message }}</div>
</template>

<style scoped>
</style>
