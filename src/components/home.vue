<script setup>
import bgsecondary from "./component/bgsecondary.vue";
import mainVue from "./main.vue";
import logo from "./logo.vue";
</script>
<template>
  <section class="box-border">
    <!-- secondary home bg -->
    <bgsecondary></bgsecondary>
    <!-- primary home bg -->
    <div
      class="absolute w-full h-[1240px] bg-cover bg-[url('https://dimas-oktavian17.github.io/assets/iconFigma/Rectangleone.svg')] top-3"
    >
      <section class="box-border pt-32">
        <mainVue></mainVue>
        <logo></logo>
      </section>
    </div>
  </section>
</template>
