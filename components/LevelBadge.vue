<template>
  <span class="inline-block py-.1 px-1 rounded-xl bg-green-100 text-xs text-gray-700"
    v-if="level === 's'">简单</span>
  <span class="inline-block py-.1 px-1 rounded-xl bg-yellow-100 text-xs text-gray-700"
    v-if="level === 'm'">中等</span>
  <span class="inline-block py-.1 px-1 rounded-xl bg-yellow-100 text-xs text-gray-700"
    v-if="level === 'h'">中等</span>
</template>
<script setup>
defineProps({
  level: {
    type: String,
    default: 's'
  },
})
</script>