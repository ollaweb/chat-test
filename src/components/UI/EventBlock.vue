<script setup>
import UserAvatar from "@/components/UI/UserAvatar.vue";
</script>

<template>
  <div>
    <p class="font-semibold">Добавлен новый сотрудник</p>
    <div
      class="my-2 flex items-center justify-between gap-x-4 rounded-xl bg-amber-100 p-4"
    >
      <div class="flex items-center gap-x-2">
        <UserAvatar />
        <p
          class="font-semibold text-blue-500 transition-colors hover:text-blue-600"
        >
          <a href="">Иванов Иван</a>
        </p>
      </div>
      <div>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="white"
          class="h-8 w-8 fill-green-300 sm:h-10 sm:w-10"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M12 9v3.75m9-.75a9 9 0 11-18 0 9 9 0 0118 0zm-9 3.75h.008v.008H12v-.008z"
          />
        </svg>
      </div>
    </div>
  </div>
</template>
