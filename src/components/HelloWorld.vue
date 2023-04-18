<script setup>
    import { ref } from "vue"

    const message = ref("message")
</script>

<template>
    <div>
        <h1>Hello World</h1>
        <p>{{ message }}</p>
    </div>
</template>

<style scoped></style>
