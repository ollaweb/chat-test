<script setup>
import HeaderChat from "@/components/HeaderChat.vue";
import BodyChat from "@/components/BodyChat.vue";
</script>

<template>
  <div class="h-[90vh] rounded-xl bg-white p-4 text-sm sm:text-base">
    <div class="flex h-full max-w-4xl flex-col">
      <HeaderChat />
      <BodyChat class="flex-1" />
    </div>
  </div>
</template>
