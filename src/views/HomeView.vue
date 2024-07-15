<script setup>
import { RouterView } from 'vue-router'
import { Icon } from '@iconify/vue'
</script>

<template>
  <div class="bg-black">
    <!-- <SideBar /> -->

    <div class="p-5">
      <div class="border-2 border-gray-200 border-dashed rounded-lg dark:border-gray-700">
        <div
          class="text-white text-4xl bg-red-500 bg-opacity-20 border rounded-lg shadow-md border-opacity-100 backdrop-blur-md border-solid border-yellow-500 py-14"
        >
          <section id="section1">
            <div class="flex flex-col md:flex-row items-center justify-center md:gap-36">
              <div class="flex flex-col items-center md:w-1/4">
                <img src="@/assets/Foto_Ivan.jpg" class="rounded-full w-32 md:w-64" alt="" />
                <span class="text-lg md:text-3xl mt-3 md:mt-5">Christian Ivan Wibowo.</span>
              </div>

              <div class="md:w-1/2">
                <p class="text-xl text-center md:text-left md:text-4xl">
                  Hello I'm a full-stack web developer
                </p>

                <div class="text-base md:text-lg text-justify m-3 md:m-0 md:mt-10">
                  As a passionate Computer Science student, I have a strong dedication to becoming a
                  successful web developer. My experience in various projects and organizations
                  focused on website development has enriched my technical skills in the world of
                  web development. I am determined to continue honing these skills and contribute to
                  innovative and impactful web projects. With a strong focus on web development, I
                  am determined to become a dedicated and productive web specialist.
                </div>

                <div class="mt-5 md:mt-10">
                  <RouterLink to="/cv">
                    <button
                      class="w-full px-8 py-3 text-lg font-bold transition-all duration-200 bg-gray-900 border-2 border-transparent sm:w-auto rounded-xl hover:bg-gray-600"
                    >
                      Download My CV
                    </button>
                  </RouterLink>
                </div>
              </div>
            </div>
          </section>

          <section id="section2" class="mt-10">
            <p class="text-center text-4xl font-bold">My Experiences</p>
            <div>
              <div class="md:mx-auto flex md:items-center justify-center my-10">
                <div
                  class="w-11/12 md:w-3/4 rounded-md shadow-lg shadow-[#FFFB73] bg-gradient-to-r from-red-500 via-[#FFA33C] to-[#FFFB73] p-1"
                >
                  <div class="flex p-10 h-full w-full justify-center bg-[#222222]">
                    <div class="flex flex-col md:flex-row gap-5 md:gap-20 text-white">
                      <div class="flex justify-center items-center md:w-1/4">
                        <div class="w-36 md:w-96">
                          <img src="@/assets/HMIF.svg" class="rounded-xl" alt="" />
                        </div>
                      </div>

                      <div class="flex flex-col gap-4 md:w-3/4">
                        <div class="text-2xl md:text-4xl font-bold text-center">
                          <span>Front End Developer</span>
                        </div>

                        <div class="text-base md:text-xl">
                          <ul>
                            <li>
                              – Front End website Informatics Student Association using InertiaJs
                              React
                            </li>
                            <li>
                              – Front End website Introduction to the Informatics Study Program
                              InertiaJs React
                            </li>
                            <li>– Chief Executive of CodeXpo</li>
                            <li>– Informatics Study Program Introduction Committee</li>
                          </ul>
                        </div>

                        <div>
                          <p class="text-2xl font-semibold">Requirement :</p>
                          <p class="text-base md:text-lg">React, Laravel, MySQL, Tailwind</p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div>
              <div class="md:mx-auto flex md:items-center justify-center my-10">
                <div
                  class="w-11/12 md:w-3/4 rounded-md shadow-lg shadow-[#FFFB73] bg-gradient-to-r from-red-500 via-[#FFA33C] to-[#FFFB73] p-1"
                >
                  <div class="flex p-10 h-full w-full justify-center bg-[#222222]">
                    <div class="flex flex-col md:flex-row gap-5 md:gap-20 text-white">
                      <div class="flex justify-center items-center md:w-1/4">
                        <div class="w-36 md:w-96">
                          <img src="@/assets/ustore.jpg" class="rounded-xl" alt="" />
                        </div>
                      </div>

                      <div class="flex flex-col gap-4 md:w-3/4">
                        <div class="text-2xl md:text-4xl font-bold text-center">
                          <span>Back End Developer</span>
                        </div>

                        <div class="text-base md:text-xl">
                          <ul>
                            <li>– Back End website Ustore using Laravel</li>
                            <li>– Back End website Ustore using Laravel</li>
                            <li>– Back End website Ustore using Laravel</li>
                          </ul>
                        </div>

                        <div>
                          <p class="text-2xl font-semibold">Requirement :</p>
                          <p class="text-base md:text-lg">Laravel, MySQL</p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div>
              <div class="md:mx-auto flex md:items-center justify-center my-10">
                <div
                  class="w-11/12 md:w-3/4 rounded-md shadow-lg shadow-[#FFFB73] bg-gradient-to-r from-red-500 via-[#FFA33C] to-[#FFFB73] p-1"
                >
                  <div class="flex p-10 h-full w-full justify-center bg-[#222222]">
                    <div class="flex flex-col md:flex-row gap-5 md:gap-20 text-white">
                      <div class="flex justify-center items-center md:w-1/4">
                        <div class="w-36 md:w-96">
                          <img src="@/assets/dpr.png" class="rounded-xl" alt="" />
                        </div>
                      </div>

                      <div class="flex flex-col gap-4 md:w-3/4">
                        <div class="text-2xl md:text-4xl font-bold text-center">
                          <span>Full Stack Developer</span>
                        </div>

                        <div class="text-base md:text-xl">
                          <ul>
                            <li>– Full Stack Admin Page Website Kendaraan</li>
                            <li>– Full Stack Admin Page Website Ortala</li>
                          </ul>
                        </div>

                        <div>
                          <p class="text-2xl font-semibold">Requirement :</p>
                          <p class="text-base md:text-lg">Laravel, MySQL, Bootstrap</p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div>
              <div class="md:mx-auto flex md:items-center justify-center my-10">
                <div
                  class="w-11/12 md:w-3/4 rounded-md shadow-lg shadow-[#FFFB73] bg-gradient-to-r from-red-500 via-[#FFA33C] to-[#FFFB73] p-1"
                >
                  <div class="flex p-10 h-full w-full justify-center bg-[#222222]">
                    <div class="flex flex-col md:flex-row gap-5 md:gap-20 text-white">
                      <div class="flex justify-center items-center md:w-1/4">
                        <div class="w-36 md:w-96">
                          <img src="@/assets/spot.png" class="rounded-xl" alt="" />
                        </div>
                      </div>

                      <div class="flex flex-col gap-4 md:w-3/4">
                        <div class="text-2xl md:text-4xl font-bold text-center">
                          <span>Front End Developer</span>
                        </div>

                        <div class="text-base md:text-xl">
                          <ul>
                            <li>– Front End website using Next.Js</li>
                            <li>– Front End website using TypeScript</li>
                          </ul>
                        </div>

                        <div>
                          <p class="text-2xl font-semibold">Requirement :</p>
                          <p class="text-base md:text-lg">Next, TypeScript, MySQL, Tailwind</p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div>
              <div class="md:mx-auto flex md:items-center justify-center my-10">
                <div
                  class="w-11/12 md:w-3/4 rounded-md shadow-lg shadow-[#FFFB73] bg-gradient-to-r from-red-500 via-[#FFA33C] to-[#FFFB73] p-1"
                >
                  <div class="flex p-10 h-full w-full justify-center bg-[#222222]">
                    <div class="flex flex-col md:flex-row gap-5 md:gap-20 text-white">
                      <div class="flex justify-center items-center md:w-1/4">
                        <div class="w-36 md:w-96">
                          <img src="" class="rounded-xl" alt="" />
                        </div>
                      </div>

                      <div class="flex flex-col gap-4 md:w-3/4">
                        <div class="text-2xl md:text-4xl font-bold text-center">
                          <span>Full Stack Developer</span>
                        </div>

                        <div class="text-base md:text-xl">
                          <ul>
                            <li>– Front End website using Next.Js</li>
                            <li>– Back End website using CMS Strapi</li>
                          </ul>
                        </div>

                        <div>
                          <p class="text-2xl font-semibold">Requirement :</p>
                          <p class="text-base md:text-lg">Next, Strapi CMS, Tailwind</p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </section>

          <section id="section3">
            <p class="text-center text-4xl mt-10 font-bold">Contact Me</p>

            <div
              class="flex flex-col md:flex-row items-center justify-center gap-10 md:gap-20 mt-10"
            >
              <a href="mailto:christ.ivan5758@gmail.com">
                <Icon icon="ic:outline-email" />
              </a>

              <a href="https://www.linkedin.com/in/christian-ivan-wibowo-94ba36184/">
                <Icon icon="mingcute:linkedin-line" />
              </a>

              <a href="https://www.instagram.com/ivan_wib/">
                <Icon icon="bi:instagram" />
              </a>

              <a href="https://wa.me/08172392397">
                <Icon icon="ic:twotone-whatsapp" />
              </a>

              <a href="https://github.com/ivanWib">
                <Icon icon="icon-park-outline:github" />
              </a>
            </div>
          </section>
        </div>
      </div>
    </div>
  </div>

  <RouterView />
</template>
