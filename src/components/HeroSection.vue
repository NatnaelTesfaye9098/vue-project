<script setup>
    import {defineProps} from 'vue';

    defineProps({
        title:{
            type: String,
            default: "Become a Vue Dev"
        },
        subtitle:{
            type: String,
            default: "Find the Vue job that fits your skills and needs"
        }
    })
</script>

<template>
    <section class="bg-green-700 py-20 mb-4 text-white">
        <div class="flex flex-col items-center ">
            <h1 class="text-4xl font-extrabold sm:text-5xl md:text-6xl font-sans">{{ title }}</h1>
            <p class="text-xl my-4">{{ subtitle }}</p>
        </div>
    </section>
</template>