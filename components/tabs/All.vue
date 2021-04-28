<template>
  <div class="grid grid-cols-6 gap-16">
    <div
      v-for="item, index in items"
      :key="item"
      class="border py-8 flex flex-col justify-center items-center item"
      :class="`item${index}`"
    >
      <img width="80" v-if="item" :src="item" alt="" />
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
        "https://devxhub.com/full_stack_development/backend/Laravel.png",
      ],
      type: Array,
    },
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
  animation-duration: .6s;
  border-radius: 5%;
}



.item1{
  transition-delay: .02s;
}

.item2{
  animation-name: example;
  transition-delay: .04s;
}

.item3{
  animation-name: example;
  transition-delay: .06s;
}

.item4{
  animation-name: example;
  transition-delay: .08s;
}

.item5{
  animation-name: example;
  transition-delay: .1s;
}

.item6{
  animation-name: example;
  transition-delay: .12s;
}

.item7{
  animation-name: example;
  transition-delay: .14s;
}

.item8{
  animation-name: example;
  transition-delay: .16s;
}
</style>