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
    <div class="text-center">{{ message }}</div>
</template>

<style scoped>
.text-center {
    text-align: center;
}
</style>
