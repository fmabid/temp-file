<template>
  <footer class="py-20">
    <div class="container mx-auto">
      <div class="grid grid-cols-4 gap-6">
        <div class="space-y-8">
          <h2 class="pb-4 border-b border-gray-400 text-xl">Home</h2>

          <ul class="space-y-2">
            <li class="text-lg" v-for="i in 4" :key="i">List {{ i }}</li>
          </ul>
        </div>

        <div class="space-y-8">
          <h2 class="pb-4 border-b border-gray-400 text-xl">Our Services</h2>

          <ul class="space-y-2">
            <li class="text-lg" v-for="i in 4" :key="i">List {{ i }}</li>
          </ul>
        </div>

        <div class="space-y-8">
          <h2 class="pb-4 border-b border-gray-400 text-xl">On Emergency</h2>

          <ul class="space-y-2">
            <li class="text-lg" v-for="i in 4" :key="i">List {{ i }}</li>
          </ul>
        </div>

        <div class="space-y-8">
          <h2 class="pb-4 border-b border-gray-400 text-xl">Address</h2>

          <p>58/27, Ghoramara, Boalia, Rajshahi-6100, Dhaka, Bangladesh.</p>

          <ul>
            <li class="link"></li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
  background: #fdf8f8;
}

ul li,
p {
  color: #797687;
}

ul li:hover {
  color: #fa7070;
  cursor: pointer;
}

.link {
  background-image: linear-gradient(15deg, #fa9770, #fa7070) !important;
  color: #fff !important;
}
</style>