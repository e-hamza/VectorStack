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
          class="w-full rounded-md flex flex-row space-x-6 pt-4 justify-between"
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

            <div class="flex flex-col space-y-3">
              <select
                class="w-full h-12 px-3 bg-[#1b1b1b] text-white rounded-lg"
                name=""
                id=""
              >
                <option value="blender">Blender</option>
              </select>
              <select
                class="w-full h-12 px-3 bg-[#1b1b1b] text-white rounded-lg"
                name=""
                id=""
              >
                <option value="blender">3.1</option>
              </select>
            </div>
          </div>
          <div class="w-full space-y-4">
            <h2 class="text-white font-ibmplexsans font-medium">
              Render Output Configuration
            </h2>
            <div class="flex flex-row items-center space-x-4">
              <h2 class="text-white w-1/3">Resolution</h2>
              <select
                class="w-full h-12 px-3 bg-[#1b1b1b] text-white rounded-lg"
                name=""
                id=""
              >
                <option value="4k">3840 x 2160</option>
                <option value="4k">1920 x 1440</option>
                <option value="4k">1920 x 1080</option>
              </select>
            </div>
            <div class="flex flex-row items-center space-x-4">
              <h2 class="text-white w-1/3">FPS</h2>
              <select
                class="w-full h-12 px-3 bg-[#1b1b1b] text-white rounded-lg"
                name=""
                id=""
              >
                <option value="4k">60</option>
                <option value="4k">30</option>
                <option value="4k">24</option>
              </select>
            </div>
            <div class="flex flex-row items-center space-x-4">
              <h2 class="text-white w-1/3">Codec</h2>
              <select
                class="w-full h-12 px-3 bg-[#1b1b1b] text-white rounded-lg"
                name=""
                id=""
              >
                <option value="4k">H264</option>
                <option value="4k">H265</option>
              </select>
            </div>
            <div class="flex flex-row items-center space-x-4">
              <h2 class="text-white w-1/3">File Type</h2>
              <select
                class="w-full h-12 px-3 bg-[#1b1b1b] text-white rounded-lg"
                name=""
                id=""
              >
                <option value="4k">MP4</option>
                <option value="4k">AVI</option>
              </select>
            </div>
            <select
              class="w-full h-12 px-3 bg-[#1b1b1b] text-white rounded-lg"
              name=""
              id=""
            >
              <option value="s3">AWS S3</option>
            </select>
            <input
              class="w-full h-12 px-3 bg-[#1b1b1b] text-white rounded-lg"
              value="/renders/personal_channel/4k/"
            />
          </div>
        </div>
        <div class="w-full h-10 flex flex-row justify-between">
          <div class="flex flex-wrap">
            <div class="flex items-center mr-4">
              <input
                id="red-radio"
                type="radio"
                value=""
                name="colored-radio"
                class="w-4 h-4 text-red-600 bg-gray-100 border-gray-300 focus:ring-red-500 dark:focus:ring-red-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
              />
              <label
                for="red-radio"
                class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                >Image</label
              >
            </div>
            <div class="flex items-center mr-4">
              <input
                id="green-radio"
                type="radio"
                value=""
                name="colored-radio"
                class="w-4 h-4 text-green-600 bg-gray-100 border-gray-300 focus:ring-green-500 dark:focus:ring-green-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"
              />
              <label
                for="green-radio"
                class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300"
                >Video</label
              >
            </div>
          </div>
          <h2 class="text-white">NEXT</h2>
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
  components: { TopMenu }
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
