<!-- eslint-disable -->
<template>
  <div class="lg:col-span-2 overflow-x-hidden lg:px-8 space-y-9">
    <div
      class="h-fit py-24 sm:py-36 relative bg-[#FFFFFF] shadow-lg rounded-lg sm:rounded-xl px-4"
    >
      <div class="w-[50%] h-[50%] flex flex-col items-center justify-center inset-0 m-auto bg-none space-y-4">
        <div
          class="clip h-44 w-44 sm:h-72 sm:w-72 rounded-full border-l-[#fee1c3] border-t-[#fee1c3] border-[20px] sm:border-[40px] border-b-[#3452FF] border-r-[#3452FF] m-auto"
        >
          <img
            class="object-cover rounded-full w-full h-full"
            src="@/assets/images/pic.png"
            alt="pic"
          />
        </div>
        <div class="text-zinc-700 text-center">
          <p class="text-xl leading-8 font-semibold">
            I'm a
            <span class="sm:text-3xl text-2xl text-[#3452FF]">Developer</span>
            also I'm a
            <span class="sm:text-3xl text-2xl text-[#3452FF]">Freelancer</span>
          </p>
        </div>
      </div>
    </div>

    <div>
      <BioGraphy />
    </div>
    <div>
      <SkillTool />
    </div>
    <div>
      <WorkProjectii />
    </div>
    <div>
      <WorkProject />
    </div>
  
    <div>
      <WorkProjectiii/>
    </div>
    <div>
      <ExperRience />
    </div>
   
    
  </div>
</template>
<!--eslint-disable-->
<script>
/* eslint-disable */
import assets from "@/assets/svgimages.js";
import BioGraphy from "@/components/biography.vue";
import SkillTool from "@/components/skilltool.vue";
import ExperRience from "@/components/experience.vue";
import WorkProject from "@/components/workproject.vue";
import WorkProjectii from "@/components/workprojectii.vue";
import WorkProjectiii from "@/components/workprojectiii.vue";

export default {
  name: "FreeLancer",
  components: {
    BioGraphy,
    WorkProjectiii,
    SkillTool,
    ExperRience,
    WorkProject,
    WorkProjectii,
  },

  data() {
    return {
      images: assets,
    };
  },
};
</script>

<style scoped>
/* eslint-disable */

.clip {
  -webkit-clip-path: polygon(0% 0%, 70% 0%, 100% 50%, 70% 100%, 0% 100%);
  clip-path: polygon(0% 0%, 70% 0%, 100% 50%, 70% 100%, 0% 100%);
}
</style>
