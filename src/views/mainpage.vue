<!-- eslint-disable -->
<template>
  <div class="w-full h-full pb-12">
    <div
      class="-top-[300px]  -left-[280px] fixed bg-[#3452FF] h-[1000px] w-[500px] rotate-[25deg] transform"
    ></div>
    <div
      class="-bottom-[300px] -right-[280px]  fixed bg-[#3452FF] h-[1000px] w-[500px] rotate-[25deg] transform"
    ></div>
    <div
      class="-top-[300px]  -z-1 hidden sm:block right-[300px]   fixed bg-[#fee1c3] h-[1500px] w-[30%] rotate-[25deg] transform"
    ></div>

    <div
      class=" mx-auto w-full pt-4 sm:pt-6 px-6 h-full grid  lg:grid-cols-3 grid-cols-1 gap-6 "
    >
      <div class="">
        <NameAbout />
      </div>
      <div  class="lg:col-span-2">
        <FreeLancer />
      </div>


    </div>
  </div>
</template>
<!--eslint-disable-->
<script>
/* eslint-disable */
import NameAbout from "@/components/nameabout.vue";
import FreeLancer from "@/components/freelancer.vue";

export default {
  name: "MainPage",
  components: {
    NameAbout,
    FreeLancer,
  },

  data() {
    return {};
  },
};
</script>

<style>
/* eslint-disable */
/*#FFECD8 */
@media (max-width:1024px) {


}
html,
body {
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background:#FFFFFF;
  z-index:-100;
  
}
html {
  overflow-x:hidden;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
::-webkit-scrollbar {
  width: 14px;
  height: 18px;
}

::-webkit-scrollbar-thumb {
  border-radius: 8px;
  background-color: rgba(0, 0, 0, 0.3);
}

::-webkit-scrollbar-track {
  border-radius: 8px;
  background-color: rgba(245, 245, 245, 0.5);
}
</style>
