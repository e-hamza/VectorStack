<template>
  <div class="bg-black w-screen h-screen">
    <div class="h-screen w-screen flex flex-col container mx-auto">
      <TopMenu />
      <div class="flex flex-col mt-24 space-y-2">
        <h1 class="text-white font-light text-4xl font-ibmplexmono mb-8">
          Create Render
        </h1>
        <div class="w-full rounded-md flex flex-col space-y-3">
          <input
            type="text"
            name=""
            id=""
            class="bg-[#1b1b1b] border-2 border-black h-12 rounded-xl px-4 text-white placeholder:text-[#8B8C92] focus:outline-none h-full"
            placeholder="Render title..."
          />
          <textarea
            class="bg-[#1b1b1b] border-2 border-black h-24 resize-none rounded-xl px-4 py-2 text-white placeholder:text-[#8B8C92] focus:outline-none h-full"
            placeholder="Render description..."
            name=""
            id=""
          >
          </textarea>
        </div>
        <div
          class="w-full rounded-md flex flex-row space-x-4 pt-4 justify-between"
        >
          <div class="w-full space-y-4">
            <h2 class="text-white font-ibmplexsans font-medium">
              Project Files
            </h2>

            <div
              class="bg-[#1b1b1b] p-4 border-2 rounded-xl border-dashed border-[#4a4a4a] space-y-2"
            >
              <div
                class="px-4 py-3 flex flex-row w-full rounded-xl border-2 border-black justify-between items-center"
              >
                <h2 class="text-white font-ibmplexsans font-semibold text-sm">
                  Rick and Morty - Spaceship through space [Part 1].blend
                </h2>
                <h2
                  class="uppercase text-white font-ibmplexsans font-bold text-xs bg-[#EF6969] px-4 py-2 rounded-md"
                >
                  Remove
                </h2>
              </div>
              <div
                class="px-4 py-3 flex flex-row w-full rounded-xl border-2 border-black justify-between items-center"
              >
                <h2 class="text-white font-ibmplexsans font-semibold text-sm">
                  Energy Drink Commercial [Part 1].blend
                </h2>
                <h2
                  class="uppercase text-white font-ibmplexsans font-bold text-xs bg-[#EF6969] px-4 py-2 rounded-md"
                >
                  Remove
                </h2>
              </div>
              <div
                class="px-4 py-3 flex flex-row w-full rounded-xl border-2 border-black justify-between items-center"
              >
                <h2 class="text-white font-ibmplexsans font-semibold text-sm">
                  Telescope Intro [4K].blend
                </h2>
                <h2
                  class="uppercase text-white font-ibmplexsans font-bold text-xs bg-[#EF6969] px-4 py-2 rounded-md"
                >
                  Remove
                </h2>
              </div>
            </div>
          </div>
          <div class="bg-gray-900 w-full">
            <h2 class="text-white font-ibmplexsans font-medium">
              Render Output Configuration
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
