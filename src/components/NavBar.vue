<script setup>
    import logo from '../assets/logo.png'
</script>

<template>
    <nav class="bg-green-700 border-b border-green-500 px-6 py-5">
        <div class="flex justify-between">
            <div class="flex w-auto space-x-2 justify-between items-center gap-3">
                <img v-bind:src="logo" alt="vue jobs" width="40" height="50">
                <p class="text-2xl font-extrabold text-white">Vue Jobs</p>
            </div>
            <ul class="w-auto flex justify-between items-center text-lg text-white gap-4 font-sans">
                <li>Home</li>
                <li>Jobs</li>
                <li>Add Job</li>
            </ul>
        </div>
    </nav>
</template>