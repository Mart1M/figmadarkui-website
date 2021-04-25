<template>
  <div>
    <div class="flex flex-col items-center mt-32 z-50 relative">
      <img src="../assets/img/logo.svg" alt="" srcset="">
      <h1 class="text-white font-bold text-4xl mb-16 mt-4">Figma Dark UI</h1>
    </div>
    <section class="grid grid-cols-1 gap-4 2xl:mx-96 2xl:px-16 lg:mx-32 mx-8 md:grid-cols-3 mb-24 l:mb:0">
      <a href="https://chrome.google.com/webstore/detail/giimcbodleepjhglbccnkccegcihjall/preview?hl=fr&authuser=0" class="flex items-center rounded-lg bg-gray-900 space-x-4 px-4 py-2">
        <img src="../assets/img/chrome.png" alt="" srcset="" class="w-8 h-8">
        <div class="flex flex-col">
          <span class="font-semibold text-white">Download for Chrome</span>
          <span class="text-sm text-gray-500">and Chromium based browsers</span>
        </div>
      </a>
      <a href="https://addons.mozilla.org/fr/firefox/addon/figma-dark-ui/" class="flex items-center rounded-lg bg-gray-900 space-x-4 px-4 py-2">
        <img src="../assets/img/firefox.png" alt="" srcset="" class="w-8 h-8">
        <div class="flex flex-col">
          <span class="font-semibold text-white">Download for Firefox</span>
        </div>
      </a>
      <a href="https://microsoftedge.microsoft.com/addons/detail/figma-dark-ui/jdegihdfbibfilefebgkdogaekboaika" class="flex items-center rounded-lg bg-gray-900 space-x-4 px-4 py-2">
        <img src="../assets/img/edge.png" alt="" srcset="" class="w-8 h-8">
        <div class="flex flex-col">
          <span class="font-semibold text-white">Download for Edge</span>
        </div>
      </a>
     
      

    </section>
     <img src="../assets/img/screen.png" alt="">

    



  </div>
</template>

<script>
export default {}
</script>

<style>
.gradient{
  background: linear-gradient(180deg, rgba(18, 18, 18, 0) 0%, #121212 100%);
}
.browser-screen{
  background: url(../assets/img/screen.png);
  height: 50%;
  background-size: cover;
  background-position: bottom 50%;
  background-repeat: no-repeat;
}
</style>
