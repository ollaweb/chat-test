<script setup>
import EventBlock from "@/components/UI/EventBlock.vue";
import ToolsPanel from "@/components/ToolsPanel.vue";
import ChatMessage from "@/components/UI/ChatMessage.vue";
import UserAvatar from "@/components/UI/UserAvatar.vue";
</script>

<template>
  <div class="flex h-1/2 flex-col gap-y-2 min-[400px]:ml-10 sm:ml-16">
    <div
      class="flex-1 overflow-y-auto pr-4 pt-4 scrollbar scrollbar-track-gray-100 scrollbar-thumb-blue-100 scrollbar-track-rounded-full scrollbar-thumb-rounded-full scrollbar-w-1 hover:scrollbar-thumb-blue-200 min-[400px]:scrollbar-w-1.5 sm:scrollbar-w-2"
    >
      <EventBlock />
      <ToolsPanel />
      <div class="my-4 flex flex-1 flex-col gap-y-6">
        <ChatMessage />
        <ChatMessage />
        <ChatMessage />
        <ChatMessage />
      </div>
    </div>
    <div class="flex w-full gap-x-2 pr-4">
      <UserAvatar />
      <form action="" method="" class="flex-1">
        <input
          type="text"
          name="message"
          placeholder="Добавить комментарий"
          class="h-full w-full rounded-3xl border py-2 px-4 outline-blue-300"
        />
      </form>
    </div>
  </div>
</template>
