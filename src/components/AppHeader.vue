<script setup lang="ts">
</script>

<template>
    <header>
        <h1>
            <span class="icon" aria-hidden="true">To do</span>
        </h1>
        <p>Lista de tareas en Vue.js 3</p>
    </header>
</template>

<style scoped>
    header {
        border-bottom: #fff 1px solid;
        color: #ffffff;
    }
    header::after {
        content: '';
        display: block;
        height: 1px;
        box-shadow: 0px 0px 10px 0px rgba(255, 255, 255, 0.75);
    }
    h1 {
        font-size: 2rem;
    }
    h1.icon {
        font-size: 1rem;
        vertical-align: middle;
    }
</style>