<template>
  <div
    class="flex flex-col justify-evenly items-center py-5 lg:px-5 border-r border-[#9ca3af33] bg-black"
  >
    <NuxtLink v-slot="{ isActive }" to="/" title="Home">
      <Icon
        class="icon"
        :name="isActive ? 'bx:home-alt-2' : 'bxs:home-alt-2'"
        :color="isActive ? '#40C1AD' : 'white'"
      />
    </NuxtLink>
    <NuxtLink v-slot="{ isActive }" to="/movie" title="Movie">
      <Icon
        class="icon"
        :name="
          isActive
            ? 'fluent:movies-and-tv-24-filled'
            : 'fluent:movies-and-tv-24-regular'
        "
        :color="isActive ? '#40C1AD' : 'white'"
      />
    </NuxtLink>
    <NuxtLink v-slot="{ isActive }" to="/tv" title="TV">
      <Icon
        class="icon"
        :name="isActive ? 'mingcute:tv-2-fill' : 'mingcute:tv-2-line'"
        :color="isActive ? '#40C1AD' : 'white'"
      />
    </NuxtLink>
    <NuxtLink v-slot="{ isActive }" to="/search" title="Search">
      <Icon
        class="icon"
        :name="isActive ? 'ri:search-fill' : 'ri:search-line'"
        :color="isActive ? '#40C1AD' : 'white'"
      />
    </NuxtLink>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
