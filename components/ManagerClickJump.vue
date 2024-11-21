<template>
  <div class="absolute top-0 right-0 h-full flex items-center justify-center w-full">
    <img src="/assets/WX20241121-100528.png"
      class="rounded-lg shadow-2xl w-94% z-1 hover:cursor-pointer" @click="openIncognitoWindow" />
  </div>
</template>
<script setup>
function openIncognitoWindow() {
  window.open('https://fineweather.pythonanywhere.com/manager', '_blank', 'noopener,noreferrer,incognito=yes');
}
</script>