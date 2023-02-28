<script setup>
import UserAvatar from "@/components/UI/UserAvatar.vue";
</script>

<template>
  <header class="flex items-center gap-x-2 py-1 sm:gap-x-4">
    <UserAvatar custom-class="bg-gray-300 hover:bg-gray-400" />
    <div>
      <h6
        class="font-semibold text-blue-500 transition-colors hover:text-blue-600"
      >
        <a href="">Битрикс 24</a>
      </h6>
      <time class="text-sm text-gray-400">16 января 09:23</time>
    </div>
  </header>
</template>
