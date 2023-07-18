<template>
    <div>
        <p>Detail for {{ id }}</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
    definePageMeta({
        layout: ''
    })
</script>

<style scoped>

</style>