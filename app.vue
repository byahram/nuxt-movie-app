<template>
  <div
    class="w-full h-full grid grid-rows-[1fr_max-content] lg:grid-cols-[max-content_1fr]"
  >
    <AppNavbar />
    <div id="app-scroller" class="relative overscroll-y-auto overflow-x-hidden">
      <NuxtPage />
    </div>
  </div>
</template>
