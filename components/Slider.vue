<template>
  <div>
    <Carousel
      :per-page="1"
      :navigate-to="someLocalProperty"
      :mouse-drag="false"
    >
      <Slide>
        <img src="https://devxhub.com/storage/uploads/sliders/1619072540-x-services-content.jpg" alt="">
      </Slide>
      <Slide>
        <img src="https://devxhub.com/storage/uploads/sliders/1619072540-x-services-content.jpg" alt="">
      </Slide>
      <Slide>
        <img src="https://devxhub.com/storage/uploads/sliders/1619072540-x-services-content.jpg" alt="">
      </Slide>
    </Carousel>
  </div>
</template>

<script>
import { Carousel, Slide } from 'vue-carousel';

export default {
  components: {
    Carousel,
    Slide
  },
};
</script>

<style>
</style>