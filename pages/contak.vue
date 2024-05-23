<template>
  <title>Program Sederhana</title>
  <div class="fixed-top">
    <input type="checkbox" id="check" />
    <nav>
      <h2
        style="position: absolute; color: antiquewhite; margin: 5px 7px 7px 10%"
      >
        Lajefa
      </h2>
      <ul>
        <li class="hamburger">
          <label for="check" class="button">
            <div></div>
            <div class="replace"></div>
            <div></div>
          </label>
        </li>
        <NuxtLink to="/"><li>Home</li></NuxtLink>
        <NuxtLink to="/Form"><li>Form</li></NuxtLink>
        <NuxtLink to="/Portfolio"><li>Porfolio</li></NuxtLink>
        <NuxtLink to="/Contak"><li>Contack</li></NuxtLink>
      </ul>
    </nav>
  </div>

  <div style="margin-top: 15%">
    <h1 class="text-center m-3">Informasi Kontak Saya</h1>
    <p class="text-center text-primary m-3">
      Berikut adalah informasi kontak dan alamat saya:
    </p>
    <div class="m-3" style="display: flex; justify-content: center">
      <ul class="list-group text-center" style="width: 50%">
        <li class="p-3 list-group-item">No Handphone: +62 857 2410 5195</li>
        <li class="p-3 list-group-item">
          Alamat: Jl. Taman Apel Hijau Blok A16 No 39 RT 15 RW 19, Vida Bekasi,
          Indonesia
        </li>
      </ul>
    </div>
    <div class="text-center m-3">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d1982.7880785137763!2d107.00000349273205!3d-6.319269828999592!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1svida%20arena!5e0!3m2!1sid!2sid!4v1716305533343!5m2!1sid!2sid"
        width="90%"
        height="500px"
        style="border: 0"
      ></iframe>
    </div>
  </div>
</template>

<style scoped>
@import "~/assets/css/style.css";
</style>