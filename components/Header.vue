<template>
  <header class="bg-[#01756C]">
    <div class="container mx-auto">
      <nav class="flex justify-between h-[100px] items-center">
        <NuxtLink to="/" class="text-2xl font-bold logo"><img src="../img/Logo.png" alt=""></NuxtLink>

        <ul class="flex gap-16 text-white font-normal font-fm">
          <li>
            <NuxtLink class="flex items-center gap-2" to="/eng-uzb">
              <p>Eng</p><i class='bx bx-transfer-alt'></i>
              <p>Uzb</p>
            </NuxtLink>
          </li>
          <li>
            <NuxtLink class="flex items-center gap-2" to="/rus-uzb">
              <p>Rus</p><i class='bx bx-transfer-alt'></i>
              <p>Uzb</p>
            </NuxtLink>
          </li>
          <li>
            <NuxtLink to="/articles">Articles</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/grammar">Grammar</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about">About Us</NuxtLink>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>
  
<script setup></script>
  
<style lang="scss" scoped>.router-link-exact-active {
  font-weight: 800;
}

.logo {
  text-decoration: none;
}

.font-fm {
  font-family: sans-serif !important;
}</style>