<script setup lang="ts">
const route = useRoute();
</script>
<template>
    <div>
        <h1>Test page</h1>
        <p>Current route: {{ route.path }}</p>
        <NuxtLink to="/">Next page</NuxtLink>
        <a href="https://nuxt.com/docs/getting-started/routing" target="_blank"
            >Learn more about Nuxt Routing</a
        >
    </div>
</template>
