<!-- eslint-disable -->
<template>
  <div
    class="h-fit overflow-hidden py-8 space-y-10 text-zinc-700 relative bg-[#FCF2E8] shadow-lg rounded-lg sm:rounded-xl px-4"
  >
    

    <div class="mx-auto w-11/12 space-y-6">
      <p class="text-sm sm:text-lg font-semibold">YouTube Clone</p>

      <div class="w-4/5 h-2/3 rounded-md sm:w-3/4 sm:h-1/2">
        <img class="rounded-md "  src="@/assets/images/Screenshot (247).png" />
      </div>
      <div class="text-sm sm:text-lg space-y-3">
        <p>
          Project link:
          <a class="text-blue-600" href="https://preemytclone.netlify.app/"
            >https://preemytclone.netlify.app/</a
          >
        </p>
        <p>A pixel perfect youtube clone using youtube api</p>
        <p>Technologies used include; HTML5/CSS, javascript, REST API</p>
      </div>
    </div>

  
  </div>
</template>
<!--eslint-disable-->
<script>
/* eslint-disable */
import assets from "@/assets/svgimages.js";
export default {
  name: "WorkProject",

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
