<script setup>

defineProps({
    die: {
        type: String,
        required: false,
        default: '',
    },
})

</script>


<template>
    <div class="feature-card text-center group size-[400px] bg-amber-100 hover:bg-amber-200 duration-200 rounded-2xl p-10">
        <div class="rounded-xl bg-green-800 mx-auto mb-4 hover:bg-green-600 duration-[500ms] group text-black flex items-center justify-center size-10">
            <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none"
                viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                <path stroke-linecap="round" stroke-linejoin="round"
                    d="M16 7a4 4 0 01-8 0M12 7v10m0 0a4 4 0 01-4 4m4-4a4 4 0 014 4" />
            </svg>
            <span class="text-xs block group-hover:text-white duration-200">check</span>
        </div>
        <h3 class="text-3xl text-gray-800 duration-200 group-hover:text-gray-500 mb-4">hellow world</h3>
        <p class="xl:text-base text-sm text-gray-600 duration-200 group-hover:text-green-800">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates est officiis culpa mollitia, dolorem tempore reiciendis dolor quaerat veniam eveniet.
        </p>
        <a href="" class="inline-block mt-6 px-6 py-2 bg-green-700 text-white font-semibold rounded-lg shadow-md hover:bg-green-800 focus:outline-none focus:ring-2 focus:ring-green-500 focus:ring-opacity-50 duration-200">
            Read More
        </a>
        <a v-if="die" href="" class="block w-full bg-red-500 p-2 rounded-sm mt-4">
            {{ die }}
        </a>
        
    </div>
</template>


<style scoped>

</style>