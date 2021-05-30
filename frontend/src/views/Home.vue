<template>
  <div id="home">
    
    <Slide />
    <div class="relative -mt-12 lg:-mt-24"></div>
    <BannerPrice />
  </div>
</template>

<script>
import Slide from '../components/homes/Slide'
import BannerPrice from '../components/homes/BannerPrice'

export default {
  name: 'Home',
  components: {
    Slide,
    BannerPrice
  }
}
</script>
<style scoped>
    #home {
      background-color: #c0dff3;
    }
    
</style>
