<script setup>
import { ref } from 'vue'

const props = defineProps({
  src: {
    type: String,
    required: true
  },
  type: {
    type: String,
    default: 'video/mp4'
  }
})

const isDev = import.meta.env.DEV;
const hasError = ref(false);

const handleError = () => {
  hasError.value = true;
};
</script>

<template>
  <div class="w-full h-full">
    <video 
      v-if="isDev && !hasError" 
      controls 
      class="w-full h-full object-cover rounded-xl shadow-2xl border border-gray-700/50" 
      @error="handleError"
    >
      <source :src="src" :type="type" @error="handleError">
      Your browser does not support the video tag.
    </video>
    <div v-else class="rounded-xl shadow-2xl border border-dashed border-gray-600/50 w-full h-full flex flex-col items-center justify-center bg-gray-900/50 min-h-[300px]">
      <div class="text-5xl mb-4">🎬</div>
      <h3 class="text-xl font-bold opacity-80">Video Placeholder</h3>
      <p class="text-sm opacity-50 mt-2">The host will play this video locally.</p>
    </div>
  </div>
</template>
