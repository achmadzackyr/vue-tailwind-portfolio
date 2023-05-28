<template>
    <div>
        <img src="../assets/imgs/avatar.jpg"
            class="w-[180px] h-[180px] sm:w-[200px] sm:h-[200px] mx-auto rounded-full shadow-md">
        <h1 class="mt-4 mb-2 text-center text-3xl sm:text-2xl uppercase font-semibold dark:text-white">Achmad Zacky Rachmatullah</h1>
        <hr class="border-1 my-4 border-gray-400 w-14 mx-auto ">
        <p class="text-center text-lg sm:text-xl text-gray-700 dark:text-gray-300">Fullstack developer with 12 years experience</p>
        <div class="text-center mt-2 text-gray-700 dark:text-white flex flex-wrap max-w-md md:max-w-lg items-center justify-center gap-2 mx-auto">
            <Badge text="C#" />
            <Badge text=".Net" />
            <Badge text="PHP" />
            <Badge text="Laravel" />
            <Badge text="Code Igniter" />
            <Badge text="React Js" />
            <Badge text="Next Js" />
            <Badge text="React Native" />
            <Badge text="Angular" />
            <Badge text="SQL Server" />
            <Badge text="MySQL" />
            <Badge text="AWS" />
        </div>
    </div>
</template>

<script setup>
    import Badge from '../components/Badge.vue';
</script>