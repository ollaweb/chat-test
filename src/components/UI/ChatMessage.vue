<script setup>
import TextButton from "@/components/UI/TextButton.vue";
import UserAvatar from "@/components/UI/UserAvatar.vue";
</script>

<template>
  <div class="flex gap-x-2">
    <UserAvatar />
    <div class="flex flex-col gap-y-0.5">
      <div class="max-w-md rounded-3xl bg-gray-100 px-4 pt-2 pb-3">
        <div class="flex gap-x-2">
          <p
            class="font-bold text-blue-500 transition-colors hover:text-blue-600"
          >
            <a href="">Иванов Иван</a>
          </p>
          <time class="text-sm text-gray-400">12:38</time>
        </div>
        <p class="mt-1 font-medium">
          <span class="text-blue-500 transition-colors hover:text-blue-600"
            ><a href="">Иванов Иван</a>,</span
          >
          Добрый день! Хорошего дня!
        </p>
      </div>
      <div class="ml-4 flex items-center gap-x-4">
        <TextButton text="Нравится" />
        <TextButton text="Ответить" />
        <TextButton text="Ещё" />
      </div>
    </div>
  </div>
</template>
