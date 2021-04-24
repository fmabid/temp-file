<template>
  <div class="h-5/6">
    <slide :data="slide" />
  </div>
</template>

<script>
import slide from "@wyhaya/vue-slide";

export default {
  components: { slide },
  data() {
    return {
      slide: [
        "https://devxhub.com/storage/uploads/sliders/1619072540-x-services-content.jpg",
        "https://devxhub.com/storage/uploads/sliders/1619072540-x-services-content.jpg",
        "https://devxhub.com/storage/uploads/sliders/1619072540-x-services-content.jpg",
      ],
    };
  },
};
</script>

<style>
</style>