<template>
  <div
    class="w-full h-full relative flex flex-row-reverse aspect-ratio-3/2 lg:aspect-ratio-25/9"
  >
    <div class="top-0 right-0" lt-lg="left-0" lg="bottom-0 left-1/3">
      <NuxtImg
        src="https://movies-proxy.vercel.app/ipx/f_webp&s_1220x659/tmdb/ottT2Yt0OfHiHp3PHJTLNVV8JPE.jpg"
        class="h-full w-[1220px] object-cover"
      ></NuxtImg>
    </div>

    <div
      class="absolute bottom-0 left-0 top-0 px-20 flex flex-col justify-center bg-gradient-to-r from-black via-black to-transparent lg:px-25 lg:w-2/3"
    >
      <Transition appear name="hero">
        <div>
          <h1 class="mt-2 text-4xl lg:text-5xl line-clamp-2">No Way Up</h1>
          <div class="flex gap-2 items-center mt-4">
            <StarsRate w-25 />
            <div class="opacity-50 hidden md:block">6.1</div>
            <span class="opacity-50 hidden md:block">·</span>
            <div class="opacity-50 hidden md:block">187 Reviews</div>
            <span class="opacity-50">·</span>
            <div class="opacity-50">2024</div>
            <span class="opacity-50">·</span>
            <div class="opacity-50">1h 30min</div>
          </div>
          <p
            class="mt-2 opacity-80 leading-relaxed of-hidden line-clamp-3 md:line-clamp-5 text-xs md:text-base pr-20"
          >
            Characters from diffe Characters from diffe Characters from diffe
            Characters from diffe Characters from diffe Characters from diffe
            Characters from diffe Characters from diffe Characters from diffe
          </p>
          <div class="py-5">
            <button
              class="flex gap2 items-center bg-[#9ca3af26] hover:bg-[#9ca3af33] transition px-5 py-2"
            >
              Watch Trailer
            </button>
          </div>
        </div>
      </Transition>
    </div>
    <div
      class="absolute left-0 top-0 right-0 h-2/3 items-center justify-center"
    >
      <button
        class="items-center p-10 text-5xl opacity-20 hover:opacity-80 transition"
      ></button>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
