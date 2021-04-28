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
  }
  to {
    transform: scale(1);
    border-radius: 5%;
    }
}

.item{
  animation-name: example;
  animation-duration: .5s;
  border-radius: 5%;
}
</style>