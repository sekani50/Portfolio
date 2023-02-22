<!-- eslint-disable -->
<template>
  <div
    class="h-fit overflow-hidden py-8 space-y-10 text-zinc-700 relative bg-[#FCF2E8] shadow-lg rounded-lg sm:rounded-xl px-4"
  >
  <p class="uppercase text-lg sm:text-xl font-semibold pb-3 border-b-4 w-32 border-[#3452FF]">Biography</p>

  <div class="w-[97%] mx-auto sm:w-11/12 space-y-6">
    <div class="text-zinc-700 bg-black bg-opacity-10 leading-6 sm:leading-10 sm:text-lg text-sm p-3 rounded-l-none sm:rounded-l-none   sm:rounded-r-lg rounded-md sm:rounded-lg border-l-4 border-l-[#3452FF]">
    I'm an
     experienced and passionate Front-End Developer. I'm always eager to apply my
      technical knowledge and expertise to create innovative and engaging web experiences. 
      I'm highly organized, detail-oriented and have excellent communicating and problem solving skills. I work well in a team environment
       and able to handle multiple tasks and projects at the same time.
  </div>

  <div class="grid grid-col-1 sm:grid-cols-2 gap-2">
    <div class="text">Name: Idris Mohammed</div>
    <p class="text">Language: English, Arabic</p>
    <p class="text">Nationality: Lagos, Nigeria</p>
    <p class="text">Phone: +2348139667165</p>
    <p class="text sm:col-span-2">Email: <a  href="https://mohammedadeoye0@gmail.com">https://mohammedadeoye0@gmail.com</a></p>
    <p class="text sm:col-span-2">Github: <a  href="https://github.com/sekani50">https://github.com/sekani50</a></p>
    <p class="text sm:col-span-2">LinkedIn: <a hrf="https://linkedin.com/in/idris-adeoye">https://linkedin.com/in/idris-adeoye</a></p>
    <p class="text sm:col-span-2">Twitter: <a  href="https://twitter.com/AdeoyeMohammed">https://twitter.com/AdeoyeMohammed</a></p>
    
  </div>
</div>
 

  </div>
</template>
<!--eslint-disable-->
<script>
/* eslint-disable */
import assets from "@/assets/svgimages.js";
export default {
  name: "BioGraphy",

  data() {
    return {
      images: assets,
    };
  },
};
</script>

<style scoped>
/* eslint-disable */

.text {
    @apply text-zinc-700 bg-black bg-opacity-10 sm:text-lg text-sm p-3 rounded-l-none sm:rounded-l-none   sm:rounded-r-lg rounded-md sm:rounded-lg border-l-4 border-l-[#3452FF];
}
</style>
