<!-- eslint-disable -->
<template>
  <div
    class="h-fit overflow-hidden py-8 space-y-10 text-zinc-700 relative bg-[#FFFFFF] shadow-lg rounded-lg sm:rounded-xl px-4"
  >
    <p
      class="uppercase text-lg sm:text-xl font-semibold pb-3 border-b-4 w-32 border-[#3452FF]"
    >
      Projects
    </p>

    <div class="mx-auto w-11/12 space-y-6">
      <p class="text-sm sm:text-lg lg:text-[15px] font-semibold">E-commerce Site</p>

      <div class="w-4/5 h-2/3 rounded-md sm:w-3/4 sm:h-1/2">
        <img class="rounded-md " src="@/assets/images/Screenshot (251).png" />
      </div>
      <div class="text-sm sm:text-lg lg:text-[15px] space-y-3">
        <p>
          Project link:
          <a class="text-blue-600" href="https://chawkbclone.netlify.app/" target="_blank"
            >https://chawkbclone.netlify.app/</a
          >
        </p>
        <p>A Chawkbazaar e-commerce site</p>
        <p>Technologies used include; HTML5/CSS, javascript, Vue and Vuex</p>
      </div>
    </div>
  </div>
</template>
<!--eslint-disable-->
<script>
/* eslint-disable */
import assets from "@/assets/svgimages.js";
export default {
  name: "WorkProjectiii",

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
  @apply text-zinc-700 truncate bg-black min-w-max bg-opacity-10 sm:text-lg text-sm p-3 rounded-r-none sm:rounded-r-none border-l-4 rounded-l-none sm:rounded-l-lg border-l-[#3452FF] sm:border-l-0 rounded-md sm:rounded-lg border-r-4 border-r-[#3452FF];
}
.span {
  @apply sm:hidden group-hover:block text-zinc-700 p-1 absolute min-w-max border rounded-sm bg-white;
}
</style>
