<template>
  <title>Program Sederhana</title>
  <div>
    <div class="fixed-top">
      <input type="checkbox" id="check" />
      <nav>
        <h2
          style="
            position: absolute;
            color: antiquewhite;
            margin: 5px 7px 7px 10%;
          "
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
    <div style="padding-top: 12%">
      <title>Program Sederhana</title>
      <h1 class="text-center m-3">Portfolio Saya</h1>
      <p class="text-center text-primary m-3">
        Selamat datang di portfolio saya. Berikut adalah beberapa proyek yang
        telah saya kerjakan:
      </p>
      <div class="m-3" style="display: flex; justify-content: center">
        <ol
          class="list-group list-group-numbered text-center"
          style="width: 50%"
        >
          <li class="p-3 list-group-item">Website Designner</li>
          <li class="p-3 list-group-item">Shooping Website</li>
          <li class="p-3 list-group-item">Software Enginering</li>
        </ol>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import "~/assets/css/style.css";
</style>

<script>
export default {};
</script>