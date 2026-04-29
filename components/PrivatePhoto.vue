<script setup>
const props = defineProps({
  src: {
    type: String,
    required: true
  },
  alt: {
    type: String,
    default: ''
  }
})

const isDev = import.meta.env.DEV;
</script>

<template>
  <div v-if="isDev" class="h-full w-full flex items-center justify-center bg-gray-100 dark:bg-gray-800 rounded-lg overflow-hidden">
    <img :src="src" :alt="alt" class="object-cover w-full h-full" />
  </div>
  <slot v-else></slot>
</template>
