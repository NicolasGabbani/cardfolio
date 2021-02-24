<template>
  <Particles
    id="tsparticles"
    :options="{
      fpsLimit: 60,
      interactivity: {
        detectsOn: 'canvas',
      },
      particles: {
        color: {
          value: '#ffffff',
        },
        collisions: {
          enable: true,
        },
        move: {
          direction: 'top',
          enable: false,
          outMode: 'out',
          random: false,
          speed: 8,
          straight: false,
        },
        number: {
          density: {
            enable: true,
            value_area: 800,
          },
          value: 20,
        },
        opacity: {
          value: 1,
          anim: {
            enable: true,
            minimumValue: 0.3
          }
        },
        shape: {
          type: 'star'
        },
        size: {
          random: {
            enable: true,
            minimumValue: 1,
          },
          value: 4,
        }
      },
      detectRetina: true,
    }"
  />
</template>

<script>
export default {
  name: 'Stars'
}
</script>