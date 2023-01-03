<script setup>
import AppHeader from "../../Layouts/AppHeader.vue";
import CHero from "./CHero.vue";
</script>
<template>
    <link
        href="https://cdn.jsdelivr.net/npm/tailwindcss/dist/tailwind.min.css"
        rel="stylesheet"
    />
    <section id="Welcome" class="bg-zinc-900">
        <div>
            <AppHeader />
            <CHero />
        </div>
    </section>
</template>

<style>
.relative {
    background-color: #ebedef;
}
</style>
