<script setup>
    import logo from '../assets/jobs.png'
</script>

<template>
    <nav class="bg-green-700 border-b border-green-500 px-6 py-5">
        <div class="flex justify-between">
            <div class="flex w-auto space-x-2 justify-between items-center gap-3">
                <div class="bg-white w-[50px] rounded-full">
                    <img v-bind:src="logo" alt="vue jobs" width="60" height="50">
                </div>
                <p class="text-2xl font-extrabold text-white">Fit Jobs</p>
            </div>
            <ul class="w-auto flex justify-between items-center text-lg text-white gap-4 font-sans font-semibold">
                <li>Home</li>
                <li>Jobs</li>
                <li>Add Job</li>
            </ul>
        </div>
    </nav>
</template>