<script setup>
// import TheWelcome from '../components/TheWelcome.vue'
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <section class="bg-black md:h-full md:w-full relative p-10">
    <div class="text-white text-center font-semibold text-xl md:text-3xl">
      Welcome To My Portfolio
    </div>

    <div class="md:mx-auto md:flex md:items-center md:justify-center my-10">
      <div
        class="w-fit rounded-md shadow-lg shadow-[#FFFB73] bg-gradient-to-r from-red-500 via-[#FFA33C] to-[#FFFB73] p-1"
      >
        <div class="flex p-10 h-full w-full justify-center bg-[#222222]">
          <div class="flex flex-col md:flex-row gap-5 md:gap-10 md:text-2xl font-black text-white">
            <div class="flex justify-center">
              <div class="w-36 md:w-96">
                <img src="@/assets/Foto_Ivan.jpg" class="rounded-xl" alt="" />
              </div>
            </div>

            <div>
              <div class="md:text-lg md:w-96 text-justify">
                As a passionate Computer Science student, I have a strong dedication to becoming a
                successful web developer. My experience in various projects and organizations
                focused on website development has enriched my technical skills in the world of web
                development. I am determined to continue honing these skills and contribute to
                innovative and impactful web projects. With a strong focus on web development, I am
                determined to become a dedicated and productive web specialist.
              </div>

              <div class="flex justify-center md:justify-end">
                <RouterLink to="/cv">
                  <button
                    class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded mt-5"
                  >
                    Resume
                  </button>
                </RouterLink>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <RouterView />
</template>
