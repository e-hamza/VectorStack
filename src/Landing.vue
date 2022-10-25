<template>
  <div class="h-screen w-screen bg-gradient-to-r from-gray-900 to-black">
    <div
      class="h-screen w-screen bg-[url('vectorstack.png')] bg-right-bottom bg-no-repeat"
    >
      <div class="flex flex-col h-screen justify-center space-y-8 ml-24">
        <img class src="@/assets/logo.png" alt="logo" width="250" />
        <h2 class="text-white text-3xl w-80">
          Distributed & Serverless Cloud Render Platform
        </h2>
        <div class="flex flex-row space-x-14">
          <h3
            class="text-white font-mono underline underline-offset-8 font-bold uppercase text-sm"
          >
            Get Started
          </h3>
          <h3
            class="text-white font-mono underline underline-offset-8 font-bold uppercase text-sm"
          >
            Documentation
          </h3>
          <h3
            class="text-white font-mono underline underline-offset-8 font-bold uppercase text-sm"
          >
            Github
          </h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  title: "Hello",
  components: {},
};
</script>

<style>
</style>
