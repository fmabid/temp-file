<template>
  <div class="grid grid-cols-6 gap-16">
    <div v-for="item in items" :key="item" class="border py-8 flex flex-col justify-center items-center item">
      <img width="80" :src="item" alt="">
    </div>
  </div>
</template>

<script>
export default {
  props: {
    items: {
      default: [
      "https://devxhub.com/full_stack_development/backend/Laravel.png",
      "https://devxhub.com/full_stack_development/backend/NodeJS.png",
      "https://devxhub.com/full_stack_development/backend/NodeJS.png",
      "https://devxhub.com/full_stack_development/backend/django.png",
      "https://devxhub.com/full_stack_development/frontend/VueJS.png",
      "https://devxhub.com/full_stack_development/frontend/ReactJS.png",
      "https://devxhub.com/full_stack_development/frontend/nuxtjs.png",
      "https://devxhub.com/full_stack_development/backend/Laravel.png"
    ],
    type: Array
    }
  },
};
</script>

<style scoped>
@keyframes example {
  from {
    transform: scale(0);
    border-radius: 80%;
    border: 25px solid black;
  }
  to {
    transform: scale(1);
    border-radius: 5%;
    border: 0 solid transparent;
    }
}

.item{
  animation-name: example;
  animation-duration: .5s;
  border-radius: 5%;
}
</style>