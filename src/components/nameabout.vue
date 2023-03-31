<!-- eslint-disable -->
<template>
  <div
    class=" lg:fixed transform transition-all duration-300 ease-linear relative lg:w-[33%] h-fit bg-[#FFFFFF] shadow-lg pt-2 pb-8 rounded-lg sm:rounded-xl px-6 space-y-10 "
  >
  <div class="w-11/12">
    <div class="rounded-full h-52 w-52 ml-10 lg:mx-auto">
      <img
        class="w-full h-full object-cover rounded-full"
        src="@/assets/images/pic.png"
        alt="pics"
      />
    </div>
  </div>
    

    <div class="w-[97%] sm:w-11/12 space-y-3 sm:space-y-6 lg:space-y-3 m-auto">
      <p class="uppercase text-xl md:text-2xl font-bold tracking-wider">
        <span class="text-[#3452FF] mr-4"> idris</span
        ><span class="text-zinc-800">mohammed</span>
      </p>

      <div
        class="text-zinc-700 leading-6 lg:leading-7 sm:leading-10 bg-black bg-opacity-10 sm:text-lg text-sm lg:text-[15px] p-3 rounded-l-none sm:rounded-l-none   sm:rounded-r-lg rounded-md sm:rounded-lg border-l-4 border-l-[#3452FF]"
      >
        I'm a frontend developer with experience in developing and designing
        complex web applications. I possess strong problem-solving and
        communication skills, and a desire to stay abreast of the latest
        technologies
      </div>
      <div class="sm:space-y-6 space-y-3 lg:space-y-3">
        <div class="flex space-x-2 p-3 lg:text-[15px] text-zinc-700 rounded-md sm:rounded-lg sm:text-lg text-sm w-full bg-opacity-10 bg-black">
          <span class="" v-html="images.tel"></span>
          <p class="">+2348139667165</p>
        </div>
        <!--
           <div class="flex min-w-max space-x-3 bg-black text-zinc-700 sm:text-lg text-sm  bg-opacity-10 px-4 p-3 rounded-md sm:rounded-lg">
          <div v-html="images.email"></div>
          <p>mohammedadeoye0@gmail.com</p>
        </div>
        -->
       
        <div class="flex space-x-2 p-3 lg:text-[15px]  text-zinc-700 sm:text-lg text-sm rounded-md bg-opacity-10 bg-black sm:rounded-lg ">
          <div class="" v-html="images.git"></div>
          <a href=" https://linkedin.com/in/idris-adeoye" class="truncate"> https://linkedin.com/in/idris-adeoye</a>
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
  name: "NameAbout",

  data() {
    return {
      images: assets,
    };
  },
};
</script>

<style scoped>
/* eslint-disable */
</style>
