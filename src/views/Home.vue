<template>
  <div class="home">
    <lottie-player src="https://assets5.lottiefiles.com/packages/lf20_KUFdS6.json"  background="transparent"  speed="1"  style="width: 200px; height: 200px;" class="cloud1" autoplay loop></lottie-player>

    <lottie-player src="https://assets5.lottiefiles.com/packages/lf20_KUFdS6.json"  background="transparent"  speed="1"  style="width: 230px; height: 230px;" class="cloud2" autoplay loop></lottie-player>

    <lottie-player src="https://assets5.lottiefiles.com/packages/lf20_KUFdS6.json"  background="transparent"  speed="0.5"  style="width: 150px; height: 150px;" class="cloud3" autoplay loop></lottie-player>

    <div class="sunshine animate__animated animate__fadeIn animate__delay-1s">
      <img :src="require('@/assets/rayon.png')" alt="">
    </div>
    
    <h1 class="nickname animate__animated animate__flipInY">Nakin</h1>
    <div class="resos">
      <a href="">Twitter</a>
      <a href="">Instagram</a>
      <a href="">Twitch</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>
