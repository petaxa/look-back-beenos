<script setup lang="ts">
const props = defineProps({
    category: String
})
</script>

<template>
    <div class="">
        <h2>{{ props.category }}</h2>
    </div>
</template>
<style scoped>
</style>