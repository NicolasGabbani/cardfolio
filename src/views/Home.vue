<template>
  <div class="home">
    <Cloud />

    <div class="sunshine animate__animated animate__fadeIn animate__delay-1s">
      <img :src="require('@/assets/rayon.png')" alt="Rayon de soleil" />
    </div>
    <h1 class="nickname animate__animated animate__flipInY">Krankhaus</h1>
    <span class="animate__animated animate__flipInX animate__delay-1s">Votre E-Girl préféré</span>

    <Social />
    <Stars />
  </div>
</template>

<script>
import Social from "@/components/Social"
import Cloud from "@/components/Cloud"
import Stars from "@/components/Stars"
export default {
  name: "Home",
  setup() {
    return {
      Social,
      Cloud,
      Stars
    };
  },
};
</script>
