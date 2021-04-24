<template>
  <div class="container">
    <div>
      <Carousel :per-page="1" :navigate-to="someLocalProperty" :mouse-drag="false">
        <Slide>
          Slide 1 Content
        </Slide>
        <Slide>
          Slide 2 Content
        </Slide>
      </Carousel>
    </div>
  </div>
</template>

<script>
// import VueCarousel from '@chenfengyuan/vue-carousel';
import { Carousel, Slide } from 'vue-carousel';

export default {
  components: {
    Carousel,
    Slide
  },
  data() {
    return {
      data: [
        '<div class="example-slide">Slide 1</div>',
        '<div class="example-slide">Slide 2</div>',
        '<div class="example-slide">Slide 3</div>',
      ],
    };
  },
}
</script>

