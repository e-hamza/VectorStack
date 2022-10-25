<template>
  <div class="flex flex-row w-full justify-between my-6 items-center">
    <div class="flex flex-row items-center">
      <img src="@/assets/logo.png" alt="" width="100" />
    </div>
    <div class="h-20 flex flex-row space-x-12 items-center">
      <div
        class="flex flex-row w-80 h-10 space-x-3 items-center bg-[#1B1B1B] px-4 rounded-xl mr-5"
      >
        <img class="h-fit" src="@/assets/img/ui/loop.png" alt="" />
        <input
          type="text"
          name=""
          id=""
          class="bg-transparent text-white placeholder:text-[#8B8C92] focus:outline-none h-full"
          placeholder="Search Renders, Gallery..."
        />
      </div>
      <h3
        class="h-max uppercase text-sm text-white font-bold align-middle font-ibmplexmono"
      >
        Dashboard
      </h3>
      <h3
        class="h-max uppercase text-sm text-white font-bold align-middle font-ibmplexmono"
      >
        Render
      </h3>
      <h3
        class="h-max uppercase text-sm text-white font-bold align-middle font-ibmplexmono"
      >
        Gallery
      </h3>
      <h3
        class="h-max uppercase text-sm text-white font-bold align-middle font-ibmplexmono"
      >
        Studio
      </h3>
      <div class="flex flex-row items-center space-x-4">
        <img
          src="@/assets/img/avatar.png"
          alt=""
          class="rounded-full ml-10"
          width="50"
        />
        <h3
          class="h-max text-sm text-white font-bold align-middle font-ibmplexmono"
        >
          Hamza
        </h3>
      </div>
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&family=IBM+Plex+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,500;1,600;1,700&display=swap");

.font-ibmplexmono {
  font-family: "IBM Plex Mono", monospace;
}

.font-ibmplexsans {
  font-family: "IBM Plex Sans", monospace;
}
</style>