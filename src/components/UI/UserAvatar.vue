<script setup>
defineProps({
  customClass: {
    type: String,
  },
});
</script>

<template>
  <a href="">
    <span
      :class="customClass"
      class="flex h-8 w-8 items-center justify-center rounded-full bg-blue-300 transition-colors hover:bg-blue-400 sm:h-12 sm:w-12"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="0"
        stroke="#9ca3a"
        class="h-3/4 w-3/4 fill-white"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M15.75 6a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0zM4.501 20.118a7.5 7.5 0 0114.998 0A17.933 17.933 0 0112 21.75c-2.676 0-5.216-.584-7.499-1.632z"
        />
      </svg>
    </span>
  </a>
</template>
