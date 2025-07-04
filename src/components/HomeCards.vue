<script setup>
    import Card from './Card.vue';
</script>
<template>
    <section class="py-4">
        <div class="w-full grid grid-cols-1 md:grid-cols-2 gap-4 p-4 md:flex-row">
            <Card>
                <h2 class="text-2xl font-bold">For Employees</h2>
                <p class="mt-2 mb-4">Browse our jobs and start your career today</p>
                <a href="" class="inline-block bg-black rounded-lg text-white px-3 py-2 w-auto box-border hover:bg-gray-600">Browse Jobs</a>
            </Card>
            <Card bg="bg-green-200">
                <h2 class="text-2xl font-bold">For Employers</h2>
                <p>List your job to find the perfect employee for the role</p>
                <a href="" class="inline-block bg-green-500 rounded-lg text-white px-3 py-1.5 w-auto box-border hover:bg-green-700">Add Job</a>
            </Card>
        </div>
    </section>
</template>