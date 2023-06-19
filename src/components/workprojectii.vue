<!-- eslint-disable -->
<template>
  <div
    class="h-fit overflow-hidden py-8 space-y-10 text-zinc-700 relative bg-[#FFFFFF] shadow-lg rounded-lg sm:rounded-xl px-4"
  >

  <p
      class="uppercase text-lg sm:text-xl font-semibold pb-3 border-b-4 w-56 border-[#3452FF]"
    >
      Works & Projects
    </p>
    <div class="mx-auto w-11/12 space-y-6">
      <p class="text-sm sm:text-lg lg:text-[15px] font-semibold">Jekaeat App</p>

      <div class="w-4/5 h-2/3 rounded-md sm:w-3/4 sm:h-1/2">
        <img class="rounded-md" src="@/assets/images/Screenshot (381).png" />
      </div>
      <div class="text-sm sm:text-lg lg:text-[15px] space-y-3">
        <p>
          Work link:
          <a
            class="text-blue-600"
            href="https://play.google.com/store/apps/details?id=com.jekaeat.jekaeat"
            target="_blank"
            >https://play.google.com/store/apps/details?id=com.jekaeat.jekaeat</a
          >
        </p>
        <p>An app for buying and selling food</p>
        <p>Technologies used include; REACT, REDUX, Web app converter</p>
        <p>
          Figma Url:
          <a
            class="text-blue-600"
            href="https://www.figma.com/file/QLF97iYKdPsMnlHf5uv0sO/JEKAEAT"
            target="_blank"
            >https://www.figma.com/file/QLF97iYKdPsMnlHf5uv0sO/JEKAEAT</a
          >
        </p>
      </div>
    </div>
  </div>
</template>
<!--eslint-disable-->
<script>
/* eslint-disable */
import assets from "@/assets/svgimages.js";
export default {
  name: "WorkProjectii",

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
  @apply text-zinc-700 truncate bg-black min-w-max bg-opacity-10 sm:text-lg text-sm p-3 rounded-l-none sm:rounded-l-none   sm:rounded-r-lg rounded-md sm:rounded-lg border-l-4 border-l-[#3452FF];
}
.span {
  @apply sm:hidden group-hover:block text-zinc-700 p-1 absolute min-w-max border rounded-sm bg-white;
}

ul.b {
  list-style-type: square;
}
</style>
