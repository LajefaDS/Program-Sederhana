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
    <UserDataForm />
  </div>
</template>

<style scoped>
@import "~/assets/css/style.css";
</style>