<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-3xl font-semibold mt-4">Visi</p>
      <p>Berdasarkan kondisi dan tantangan saat ini yang kami hadapi dalam lima tahun  kedepan serta dengan mempertimbangkan potensi dan masalah yang dimiliki Desa Cibitung Tengah, kami telah merumuskan visi yaitu :</p>
      <p>“BERSAMA MEMBANGUN DESA CIBITUNG TENGAH LEBIH MAJU”</p>
      <p>Visi tersebut yang mengandung makna bersama-sama dengan berbagai elemen masyarakat untuk merencanakan, merumuskan, melaksanakan, mengawasi, pembangunan desa cibitung tengah ke arah yang lebih baik</p>
      <p class="text-3xl font-semibold mt-4">Misi</p>
      <ul>
        <li>1. meningkatkan pelayanan kepada masyarakat secara responsive, partisipasif dan ramah</li>
        <li>2.	meningkatkan kerjasama antar lembaga di Desa Cibitung Tengah, juga lembaga antar Desa</li>
        <li>3.	menumbuh kembangkan peran serta masyarakat dalam kegiatan sosial, lingkungan Hidup, Ekonomi dan keagamaan.</li>
      </ul>
     

      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/stok-cibitungtengah.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
