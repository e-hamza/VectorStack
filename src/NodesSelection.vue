<template>
  <div class="bg-black w-screen h-screen">
    <div class="h-screen w-screen flex flex-col container mx-auto">
      <TopMenu />
      <div class="flex flex-col mt-24 space-y-2">
        <h1 class="text-white font-light text-4xl font-ibmplexmono mb-8">
          Nodes Selection
        </h1>
        <div class="w-full rounded-md flex flex-row space-x-4">
          <div class="h-full w-full">
            <h2 class="text-white text-xl font-ibmplexsaans mb-4">
              Selected Nodes
            </h2>
            <div class="flex flex-col space-y-3">
              <div class="w-full h-fit bg-[#1b1b1b] py-4 px-5 rounded-xl">
                <h2 class="text-white font-bold text-xl font-ibmplexmono">
                  2x RTX 3090 • 64 Cores
                </h2>
                <h3 class="text-white text-md font-ibmplexmono">
                  32GB [DDR4] • 780Gb [2567MB/s]
                </h3>
                <h3 class="text-white text-md font-ibmplexmono">
                  ↑ 853 Mbps • ↓ 712 Mbps
                </h3>
                <div class="mt-3 flex flex-row space-x-2 justify-between">
                  <div class="flex flex-row items-center">
                    <h3
                      class="w-fit px-4 py-1 bg-[#99BDA7] rounded-full font-bold text-white text-md uppercase font-ibmplexmono"
                    >
                      ON DEMAND
                    </h3>
                    <h3
                      class="w-fit px-4 py-1 rounded-full font-bold text-white text-md uppercase font-ibmplexmono"
                    >
                      $0.374/hr
                    </h3>
                  </div>
                  <h3
                    class="w-fit px-8 py-3 bg-[#232323] rounded-lg font-bold text-white text-md uppercase font-ibmplexmono"
                  >
                    REMOVE
                  </h3>
                </div>
              </div>
              <div class="w-full h-fit bg-[#1b1b1b] py-4 px-5 rounded-xl">
                <h2 class="text-white font-bold text-xl font-ibmplexmono">
                  2x RTX 3090 • 64 Cores
                </h2>
                <h3 class="text-white text-md font-ibmplexmono">
                  32GB [DDR4] • 780Gb [2567MB/s]
                </h3>
                <h3 class="text-white text-md font-ibmplexmono">
                  ↑ 853 Mbps • ↓ 712 Mbps
                </h3>
                <div class="mt-3 flex flex-row space-x-2 justify-between">
                  <div class="flex flex-row items-center">
                    <h3
                      class="w-fit px-4 py-1 bg-[#99BDA7] rounded-full font-bold text-white text-md uppercase font-ibmplexmono"
                    >
                      ON DEMAND
                    </h3>
                    <h3
                      class="w-fit px-4 py-1 rounded-full font-bold text-white text-md uppercase font-ibmplexmono"
                    >
                      $0.374/hr
                    </h3>
                  </div>
                  <h3
                    class="w-fit px-8 py-3 bg-[#232323] rounded-lg font-bold text-white text-md uppercase font-ibmplexmono"
                  >
                    REMOVE
                  </h3>
                </div>
              </div>
              <div class="w-full h-fit bg-[#1b1b1b] py-4 px-5 rounded-xl">
                <h2 class="text-white font-bold text-xl font-ibmplexmono">
                  2x RTX 3090 • 64 Cores
                </h2>
                <h3 class="text-white text-md font-ibmplexmono">
                  32GB [DDR4] • 780Gb [2567MB/s]
                </h3>
                <h3 class="text-white text-md font-ibmplexmono">
                  ↑ 853 Mbps • ↓ 712 Mbps
                </h3>
                <div class="mt-3 flex flex-row space-x-2 justify-between">
                  <div class="flex flex-row items-center">
                    <h3
                      class="w-fit px-4 py-1 bg-[#99BDA7] rounded-full font-bold text-white text-md uppercase font-ibmplexmono"
                    >
                      ON DEMAND
                    </h3>
                    <h3
                      class="w-fit px-4 py-1 rounded-full font-bold text-white text-md uppercase font-ibmplexmono"
                    >
                      $0.374/hr
                    </h3>
                  </div>
                  <h3
                    class="w-fit px-8 py-3 bg-[#232323] rounded-lg font-bold text-white text-md uppercase font-ibmplexmono"
                  >
                    REMOVE
                  </h3>
                </div>
              </div>
            </div>
          </div>
          <div class="h-full w-full">
            <h2 class="text-white text-xl font-ibmplexsaans mb-4">
              Select Nodes
            </h2>
            <div class="flex flex-col space-y-3">
              <div class="w-full h-fit bg-[#1b1b1b] py-4 px-5 rounded-xl">
                <h2 class="text-white font-bold text-xl font-ibmplexmono">
                  2x RTX 3090 • 64 Cores
                </h2>
                <h3 class="text-white text-md font-ibmplexmono">
                  32GB [DDR4] • 780Gb [2567MB/s]
                </h3>
                <h3 class="text-white text-md font-ibmplexmono">
                  ↑ 853 Mbps • ↓ 712 Mbps
                </h3>
                <div class="mt-3 flex flex-row space-x-2 justify-between">
                  <div class="flex flex-row items-center">
                    <select
                      class="w-64 px-4 py-3 bg-[#141414] rounded-lg font-bold text-white text-md uppercase font-ibmplexmono"
                      name=""
                      id=""
                    >
                      <option>ON DEMAND [$0.647]</option>
                      <option>SPOT [$0.261]</option>
                    </select>
                  </div>
                  <h3
                    class="w-fit px-8 py-3 bg-[#7900FF] rounded-lg font-bold text-white text-md uppercase font-ibmplexmono"
                  >
                    ADD NODE
                  </h3>
                </div>
              </div>
              <div class="w-full h-fit bg-[#1b1b1b] py-4 px-5 rounded-xl">
                <h2 class="text-white font-bold text-xl font-ibmplexmono">
                  2x RTX 3090 • 64 Cores
                </h2>
                <h3 class="text-white text-md font-ibmplexmono">
                  32GB [DDR4] • 780Gb [2567MB/s]
                </h3>
                <h3 class="text-white text-md font-ibmplexmono">
                  ↑ 853 Mbps • ↓ 712 Mbps
                </h3>
                <div class="mt-3 flex flex-row space-x-2 justify-between">
                  <div class="flex flex-row items-center">
                    <select
                      class="w-64 px-4 py-3 bg-[#141414] rounded-lg font-bold text-white text-md uppercase font-ibmplexmono"
                      name=""
                      id=""
                    >
                      <option>ON DEMAND [$0.647]</option>
                      <option>SPOT [$0.261]</option>
                    </select>
                  </div>
                  <h3
                    class="w-fit px-8 py-3 bg-[#7900FF] rounded-lg font-bold text-white text-md uppercase font-ibmplexmono"
                  >
                    ADD NODE
                  </h3>
                </div>
              </div>
              <div class="w-full h-fit bg-[#1b1b1b] py-4 px-5 rounded-xl">
                <h2 class="text-white font-bold text-xl font-ibmplexmono">
                  2x RTX 3090 • 64 Cores
                </h2>
                <h3 class="text-white text-md font-ibmplexmono">
                  32GB [DDR4] • 780Gb [2567MB/s]
                </h3>
                <h3 class="text-white text-md font-ibmplexmono">
                  ↑ 853 Mbps • ↓ 712 Mbps
                </h3>
                <div class="mt-3 flex flex-row space-x-2 justify-between">
                  <div class="flex flex-row items-center">
                    <select
                      class="w-64 px-4 py-3 bg-[#141414] rounded-lg font-bold text-white text-md uppercase font-ibmplexmono"
                      name=""
                      id=""
                    >
                      <option>ON DEMAND [$0.647]</option>
                      <option>SPOT [$0.261]</option>
                    </select>
                  </div>
                  <h3
                    class="w-fit px-8 py-3 bg-[#7900FF] rounded-lg font-bold text-white text-md uppercase font-ibmplexmono"
                  >
                    ADD NODE
                  </h3>
                </div>
              </div>
            </div>
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
