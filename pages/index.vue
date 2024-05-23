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
  <div>
    <div
      class="d-flex justify-content-center align-items-center"
      style="height: 50vh; width: 95%; font-size: 28px"
    >
      <h2>
        <marquee behavior="slide">Hai, Selamat Datang di Website Saya!</marquee>
      </h2>
    </div>
  </div>
  <div style="width: 100%; display: flex; justify-content: center">
    <div
      style="
        width: auto;
        display: flex;
        justify-content: center;
        align-items: center;
      "
    >
      <iframe
        src="https://giphy.com/embed/QTlmH8hEoVoi83mdJC"
        width="170%"
        height="170%"
      ></iframe>
    </div>
  </div>
</template>

<style scoped>
@import "~/assets/css/style.css";
</style>