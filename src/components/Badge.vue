<script setup>
defineProps({
  text: String,
})

</script>

<template>
    <span class="px-2 border-2 border-blue-600 text-sm rounded-full hover:bg-blue-600 hover:text-white hover:transition-all hover:duration-300 dark:text-white">{{ text }}</span>
</template>