<template>
  <div class="bg-black w-screen h-screen">
    <div class="h-screen w-screen flex flex-col container mx-auto">
      <TopMenu />
      <div class="flex flex-col mt-24 space-y-2">
        <h1 class="text-white font-light text-4xl font-ibmplexmono mb-8">
          Renders
        </h1>
        <div
          class="w-full bg-[#070707] rounded-md py-8 flex flex-col space-y-10"
        >
          <div class="flex flex-row justify-between items-center px-10">
            <div class="w-1/3 flex flex-col">
              <h2 class="text-white text-lg font-ibmplexsans">
                Rick and Morty Fan Animation
              </h2>
              <p class="text-[#7A7A7A]">
                Rick showing morty how his gun works but he is drunk
              </p>
            </div>
            <h2
              class="bg-[#202020] h-fit text-white font-ibmplexmono font-bold text-xs px-2 py-0.5"
            >
              Blender 3.1
            </h2>
            <h2
              class="bg-[#202020] h-fit text-white font-ibmplexmono font-bold text-xs px-2 py-0.5"
            >
              4K
            </h2>
            <h2
              class="bg-[#202020] h-fit text-white font-ibmplexmono font-bold text-xs px-2 py-0.5"
            >
              60FPS
            </h2>
            <div class="flex flex-row items-center space-x-2">
              <div class="bg-[#7900FF] w-2 h-2 rounded-full"></div>
              <h2 class="text-white text-xs font-bold">Running | 16 minutes</h2>
            </div>
            <h2
              class="text-white bg-[#7900FF] uppercase text-xs font-bold px-4 py-2 rounded-lg"
            >
              Manage
            </h2>
          </div>
          <div class="h-px w-full bg-[#202020]"></div>
          <div class="flex flex-row justify-between items-center px-10">
            <div class="w-1/3 flex flex-col">
              <h2 class="text-white text-lg font-ibmplexsans">
                1440p Animated Wallpaper (Donuts)
              </h2>
              <p class="text-[#7A7A7A]">To use for my new setup!</p>
            </div>
            <h2
              class="bg-[#202020] h-fit text-white font-ibmplexmono font-bold text-xs px-2 py-0.5"
            >
              Blender 3.1
            </h2>
            <h2
              class="bg-[#202020] h-fit text-white font-ibmplexmono font-bold text-xs px-2 py-0.5"
            >
              4K
            </h2>
            <h2
              class="bg-[#202020] h-fit text-white font-ibmplexmono font-bold text-xs px-2 py-0.5"
            >
              60FPS
            </h2>
            <div class="flex flex-row items-center space-x-2">
              <div class="bg-[#7900FF] w-2 h-2 rounded-full"></div>
              <h2 class="text-white text-xs font-bold">Running | 16 minutes</h2>
            </div>
            <h2
              class="text-white bg-[#7900FF] uppercase text-xs font-bold px-4 py-2 rounded-lg"
            >
              Manage
            </h2>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import TopMenu from "@/components/TopMenu.vue";
export default {
  name: "App",
  title: "Hello",
  components: { TopMenu },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&family=IBM+Plex+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,500;1,600;1,700&display=swap");

.font-ibmplexmono {
  font-family: "IBM Plex Mono", monospace;
}

.font-ibmplexsans {
  font-family: "IBM Plex Sans", monospace;
}
</style> 
