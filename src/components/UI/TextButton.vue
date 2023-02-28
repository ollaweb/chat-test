<script setup>
defineProps({
  text: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <button type="button" class="text-xs text-gray-400 sm:text-sm">
    {{ text }}
  </button>
</template>
