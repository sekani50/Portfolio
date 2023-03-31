<!-- eslint-disable -->
<template>
  <div
    class="h-fit overflow-hidden py-8 space-y-10 text-zinc-700 relative bg-[#FFFFFF] shadow-lg rounded-lg sm:rounded-xl px-4"
  >
    <p
      class="uppercase text-lg sm:text-xl font-semibold pb-3 border-b-4 w-48 border-[#3452FF]"
    >
      Skillset & Tools
    </p>
    <div class="w-[95%] m-auto">
        <div class=" grid grid-cols-3 sm:grid-cols-4 gap-16">
        <div class="h-16 w-16 group relative">
            <img :src="images.html" />
            <span class="span">HTML 5</span>
        </div>
        <div class="h-16 w-16 group relative" >
            <img :src="images.css" />
            <span class="span">CSS</span>
        </div>
        <div class="h-16 w-16 group relative">
            <img :src="images.js" />
            <span class="span">Javascript</span>
        </div>
        <div class="h-16 w-16 group relative">
            <img :src="images.tail" />
            <span class="span">Tailwind CSS</span>
        </div>
        <div class="h-16 w-16 group relative">
            <img :src="images.gith" />
            <span class="span">Git</span>
        </div>
        <div class="h-16 w-16 group relative">
            <img :src="images.python" />
            <span class="span">Python</span>
        </div>
        <div class="h-16 w-16 group relative">
            <img src="@/assets/images/vueroute.png" />
            <span class="span">Vue Router</span>
        </div>
        <div class="h-16 w-16 group relative">
            <img src="@/assets/logo.png" />
            <span class="span">Vue</span>
        </div>
        <div class="h-16 w-16 group relative">
            <img :src="images.react" />
            <span class="span">React</span>
        </div>
        <div class="h-16 w-16 group relative">
            <img :src="images.post" />
            <span class="span">Postman</span>
        </div>


       
    </div>

    </div>
   
  </div>
</template>
<!--eslint-disable-->
<script>
/* eslint-disable */
import assets from "@/assets/svgimages.js";
export default {
  name: "SkillTool",

  data() {
    return {
      images: assets,
    };
  },
};
</script>

<style scoped>
/* eslint-disable */

.span {
    @apply hidden group-hover:block text-zinc-700 p-1 absolute min-w-max border rounded-sm bg-white;
}
</style>
