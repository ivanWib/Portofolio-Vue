//
<script setup>
// // import TheWelcome from '../components/TheWelcome.vue'
// import { RouterLink, RouterView } from 'vue-router'
//
</script>

<style>
/* Import styles.css atau tambahkan gaya langsung di sini */
@import '../assets/styles.css';
</style>

<script>
export default {
  name: 'App',
  data() {
    return {
      dots: [], // Array untuk menyimpan informasi titik-titik
      colors: ['#ff0000', '#00ff00', '#0000ff'] // Warna yang akan digunakan secara bergantian
    }
  },
  mounted() {
    // Membuat 10 titik-titik acak saat komponen dipasang
    this.generateRandomDots(200)

    // Memulai animasi berkedip secara bergantian
    setInterval(this.toggleBlink, 1000) // Ganti warna setiap detik (1000 milidetik)
  },
  methods: {
    generateRandomDots(count) {
      for (let i = 0; i < count; i++) {
        this.dots.push({
          id: i,
          top: `${Math.random() * 100}%`, // Nilai acak untuk posisi top
          left: `${Math.random() * 100}%`, // Nilai acak untuk posisi left
          color: this.colors[i % this.colors.length] // Bergantian antara tiga warna
        })
      }
    },
    toggleBlink() {
      // Mengubah visibilitas berkedip (bergantian setiap detik)
      this.dots.forEach((dot) => {
        dot.visible = !dot.visible
      })
    }
  }
}
</script>

<template>
  <div id="app">
    <!-- Konten utama Anda di sini -->
    <router-view />

    <!-- Komponen berkedip dengan titik-titik dan teks -->
    <div class="blinking-dots">
      <div
        v-for="dot in dots"
        :key="dot.id"
        class="dot"
        :style="{ top: dot.top, left: dot.left, backgroundColor: dot.color }"
      ></div>

      <div
        class="text-white text-4xl absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 bg-red-500 bg-opacity-20 border rounded-lg shadow-md border-opacity-100 backdrop-blur-md border-solid border-yellow-500 p-5"
      >
        <span class="">Hello, I'm </span>
        <span>Christian Ivan Wibowo</span>
        <span>.</span> <br />

        <span>I'm a full-stack web developer.</span>
      </div>

      <!-- <div class="text-white text-4xl">heeh</div> -->
    </div>
  </div>

  <RouterView />
</template>
