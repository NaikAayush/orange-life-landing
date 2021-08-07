<template>
  <router-view />
</template>

<script>
import AOS from 'aos'
import { focusHandling } from 'cruip-js-toolkit'

export default {
  mounted() {
    AOS.init({
      once: true,
      disable: 'phone',
      duration: 600,
      easing: 'ease-out-sine',
    })    
    if (this.$router) {
      this.$watch('$route', () => {
        this.$nextTick(() => {
          focusHandling('outline')
        })
      });
    }    
  }
}
</script>

