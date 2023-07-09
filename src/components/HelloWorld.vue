<template>
    <h1>Hello Wizard</h1>
    <p>{{ props.subTitle }}</p>
</template>

<script setup>
    const props = defineProps(['subTitle']);
</script>

<style scoped>
</style>