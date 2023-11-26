<script setup>
// import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <section class="bg-black h-screen w-screen relative p-10">
    <div class="text-white text-center text-3xl">Welcome To My Portfolio</div>

    <div class="mx-auto flex items-center justify-center my-10">
      <div
        class="w-fit rounded-md shadow-lg shadow-[#FFFB73] bg-gradient-to-r from-red-500 via-[#FFA33C] to-[#FFFB73] p-1"
      >
        <div class="flex p-10 h-full w-full justify-center bg-[#222222]">
          <div class="flex gap-10 text-2xl font-black text-white">
            <div class="w-96">
              <img src="@/assets/Foto_Ivan.jpg" class="rounded-xl" alt="" />
            </div>

            <div>
              <div class="text-lg w-96">
                As a passionate Computer Science student, I have a strong dedication to becoming a
                successful web developer. My experience in various projects and organizations
                focused on website development has enriched my technical skills in the world of web
                development. I am determined to continue honing these skills and contribute to
                innovative and impactful web projects. With a strong focus on web development, I am
                determined to become a dedicated and productive web specialist.
              </div>

              <button
                class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded mt-5"
              >
                Resume
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
