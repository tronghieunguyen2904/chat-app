<script setup lang="ts">
import SidebarChat from '@/components/SidebarChat.vue'
import ChatRoom from '@/components/ChatRoom.vue'
</script>

<template>
<!-- component -->
<div class="flex h-screen antialiased text-gray-800">
    <div class="flex flex-row h-full w-full overflow-x-hidden">
      <!-- Sidebar Chat -->
      <SidebarChat></SidebarChat>

      <!-- Chat Room -->
      <ChatRoom></ChatRoom>
    </div>
  </div>
</template>
