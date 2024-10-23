<script setup>
defineProps({
    user: String
})
</script>

<template>
    <Head title=" | About"/>
    <h1>About page {{ user }}</h1>
</template>
