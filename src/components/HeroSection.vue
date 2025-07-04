<script setup>
    import {defineProps} from 'vue';

    defineProps({
        title:{
            type: String,
            default: "Jobs That Match You"
        },
        subtitle:{
            type: String,
            default: "Browse carefully selected listings that match your skills and goals"
        }
    })
</script>

<template>
    <section class="bg-green-700 py-20 mb-4 text-white">
        <div class="flex flex-col items-center leading-loose">
            <h1 class="text-3xl font-extrabold sm:text-5xl md:text-6xl font-sans">{{ title }}</h1>
            <p class="text-xl my-4">{{ subtitle }}</p>
        </div>
    </section>
</template>