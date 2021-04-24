<template>
  <div class="relative">
    <Slider />

    <section class="relative py-10 sec-2">
      <div class="container mx-auto">
        <div class="flex flex-row">
          <div class="w-2/3 p-10 space-y-4">
            <h2 class="text-4xl">
              Welcome to <span class="corolMain">DevXHub</span>
            </h2>
            <h5 class="text-2xl">
              The Largest & Effective IT Solution Company In Bangladesh.
            </h5>
            <p class="text-normal leading-7">
              DevXHub, a well-acclaimed company successfully delivering
              unmatched quality service in IT for the last couple of years. We
              are among the most renowned & trusted names in Domain
              Registration, Web Hosting, Graphics Design, Web Design, Web
              Development, Theme Development, Software Development, Mobile Apps
              Development, eCommerce Solutions, Search Engine Optimization & any
              others IT Solution services in the World. We are very grateful to
              you for taking the time to consider us for your professional
              needs. DevXHub only exists because of our obligation to you, the
              client. Your needs are our needs, and no expenditure is spared in
              gathering these needs
            </p>

            <button class="btnDetails py-2 px-4 rounded-full">
              View Details
            </button>
          </div>

          <div class="w-1/3">
            <img
              src="https://devxhub.com/storage/uploads/welcome/1619092067-413x516-about_image.jpg"
              alt=""
            />
          </div>
        </div>
      </div>
    </section>

    <section class="relative py-20 sec-3">
      <div class="container mx-auto">
        <div class="grid grid-cols-2 gap-10">
          <div class="relative space-y-10">
            <h2 class="text-4xl font-bold">
              <span class="corolMain">OUR</span> MISSION
            </h2>

            <ul class="space-y-4">
              <li class="space-x-4">
                <img
                  src="https://devxhub.com/frontend/assets/img/check-mark.svg"
                  alt=""
                />
                <span
                  >To work constantly in achieving the highest quality
                  Support.</span
                >
              </li>
              <li class="space-x-4">
                <img
                  src="https://devxhub.com/frontend/assets/img/check-mark.svg"
                  alt=""
                />
                <span
                  >To encourage creativity, ethics and value in our organization
                  and ensure accountability of each employee towards the goals
                  of the company.</span
                >
              </li>
              <li class="space-x-4">
                <img
                  src="https://devxhub.com/frontend/assets/img/check-mark.svg"
                  alt=""
                />
                <span
                  >To constantly strive, innovate and introduce latest modern
                  technology in harmony with requirements of future.</span
                >
              </li>
              <li class="space-x-4">
                <img
                  src="https://devxhub.com/frontend/assets/img/check-mark.svg"
                  alt=""
                />
                <span
                  >To establish ourselves as one of the key players in the IT
                  Sector.</span
                >
              </li>
              <li class="space-x-4">
                <img
                  src="https://devxhub.com/frontend/assets/img/check-mark.svg"
                  alt=""
                />
                <span
                  >To become top quality IT organization by building standards
                  in quality and reliability for products and services.</span
                >
              </li>
              <li class="space-x-4">
                <img
                  src="https://devxhub.com/frontend/assets/img/check-mark.svg"
                  alt=""
                />
                <span>To provide the finest IT solutions globally.</span>
              </li>
            </ul>
          </div>

          <div class="relative space-y-10">
            <h2 class="text-4xl font-bold">
              <span class="corolMain">OUR</span> VISION
            </h2>

            <ul class="space-y-4">
              <li class="space-x-4">
                <img
                  src="https://devxhub.com/frontend/assets/img/check-mark.svg"
                  alt=""
                />
                <span
                  >To provide the highest quality Hosting & Other related
                  services at most competitive rates and to ensure that the
                  services are delivered with best quality On Time, Every
                  Time.</span
                >
              </li>
              <li class="space-x-4">
                <img
                  src="https://devxhub.com/frontend/assets/img/check-mark.svg"
                  alt=""
                />
                <span
                  >To be known in the industry as trustworthy and to be quality
                  and service oriented</span
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section class="relative py-20 sec-4">
      <div class="container mx-auto text-center">
        <h3 class="text-3xl font-bold">Services</h3>

        <div class="grid grid-cols-3 gap-14 mt-10">
          <div
            v-for="i in 12"
            :key="i"
            class="card rounded-lg border p-4 shadow flex flex-col align-middle items-center space-y-4"
          >
            <img
              class="w-1/4"
              src="https://devxhub.com/storage/uploads/services/1617294414-96x96-group-2118.png"
              alt=""
            />

            <div class="relative space-y-4">
              <h5 class="font-bold text-xl">Domain and Hosting</h5>
              <p class="text-sm">
                You can buy any sorts of domain, and hosting from us. We,re the
                best, and reliable domain, and hosting service provider Company
                in Bangladesh.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="relative py-20 sec-5">
      <div class="container mx-auto text-center">
        <h3 class="text-3xl font-bold">
          Technology <span class="corolMain">We Used</span>
        </h3>

        <div class="grid grid-cols-3 gap-14 mt-10">
          <div
            v-for="i in 9"
            :key="i"
            class="bg-white card rounded-lg border px-4 py-10 shadow flex flex-col align-middle items-center space-y-6"
          >
            <img
              class="w-1/4 border rounded"
              src="https://devxhub.com/storage/uploads/SkillOrTechnology/1616083284-90x90-robot-removebg-preview.png"
              alt=""
            />

            <h5 class="font-bold text-xl">Domain and Hosting</h5>
          </div>
        </div>
      </div>
    </section>

    <section class="relative py-20 sec-6">
      <div class="container mx-auto text-center space-y-12">
        <h3 class="text-3xl font-bold">
          <span class="corolMain">Technology</span> Stacks
        </h3>

        <div class="relative">
          <ul class="flex flex-row items-center justify-between">
            <li
              v-for="tab in tabs"
              v-bind:key="tab"
              :class="[
                'font-bold cursor-pointer py-1 px-5 rounded-full',
                { 'tab-button': currentTab === tab },
              ]"
              @click="currentTab = tab"
            >
              {{ tab }}
            </li>
          </ul>

          <component v-bind:is="currentTabComponent" class="py-10"></component>
        </div>
      </div>
    </section>

    <section class="relative py-20 sec-7">
      <div class="container mx-auto text-center space-y-16">
        <h3 class="text-4xl font-bold">
          We Always Try to Understand
          <div class="corolMain">Users Expectation</div>
        </h3>

        <div class="grid grid-cols-4 gap-10 text-center">
          <div class="product space-y-2">
            <h4 class="text-5xl text-blue-800">10 +</h4>
            <h5 class="text-xl">Mobile Apps</h5>
            <p class="text-sm">Since 2015</p>
          </div>
          <div class="product space-y-2">
            <h4 class="text-5xl text-pink-500">15 +</h4>
            <h5 class="text-xl">Dedicated Developer</h5>
            <p class="text-sm">On Our Own Solutions</p>
          </div>
          <div class="product space-y-2">
            <h4 class="text-5xl text-pink-500">50 +</h4>
            <h5 class="text-xl">Employees</h5>
            <p class="text-sm">Spread Over 4 Hubs</p>
          </div>
          <div class="product space-y-2">
            <h4 class="text-5xl text-green-500">200 +</h4>
            <h5 class="text-xl">Mobile Apps</h5>
            <p class="text-sm">Delivered Application</p>
          </div>
          <div class="product space-y-2">
            <h4 class="text-5xl text-green-500">14 M+</h4>
            <h5 class="text-xl">Line Of Codes</h5>
          </div>
          <div class="product space-y-2">
            <h4 class="text-5xl text-green-500">35 +</h4>
            <h5 class="text-xl">Completed Project</h5>
            <p class="text-sm">Since 2015</p>
          </div>
          <div class="product space-y-2">
            <h4 class="text-5xl text-pink-500">6 +</h4>
            <h5 class="text-xl">Ongoing Project</h5>
            <p class="text-sm">Since 2015</p>
          </div>
          <div class="product space-y-2">
            <h4 class="text-5xl corolMain">300 +</h4>
            <h5 class="text-xl">Clients</h5>
            <p class="text-sm">Since 2015</p>
          </div>
        </div>
      </div>
    </section>

    <section class="relative py-20 sec-8">
      <div class="container mx-auto text-center space-y-16">
        <h3 class="text-4xl font-bold corolMain">
          Subscribe for our Newsletter
        </h3>

        <div class=" space-x-2">
          <input class="text-xl" placeholder="Enter your email address" type="email">
          <button class="btnDetails py-4 px-12 rounded-full">
              View Details
            </button>
        </div>
      </div>
    </section>
    
    <Footer/>
  </div>
</template>

<script>
import Footer from '~/components/Footer.vue';
import Slider from "~/components/Slider2.vue";
import All from "~/components/tabs/All.vue";
import Animations from "~/components/tabs/Animations.vue";
import Backend from "~/components/tabs/Backend.vue";
import Cloud from "~/components/tabs/Cloud.vue";
import CMS from "~/components/tabs/CMS.vue";
import CSS from "~/components/tabs/CSS.vue";
import Database from "~/components/tabs/Database.vue";
import DevOps from "~/components/tabs/DevOps.vue";
import Frontend from "~/components/tabs/Frontend.vue";
import Testing from "~/components/tabs/Testing.vue";
import Tools from "~/components/tabs/Tools.vue";

export default {
  components: {
    Slider,
    All,
    Animations,
    Backend,
    Cloud,
    CMS,
    CSS,
    Database,
    DevOps,
    Frontend,
    Testing,
    Tools,
    Footer,
  },
  data() {
    return {
      currentTab: "All",
      tabs: [
        "All",
        "Backend",
        "Frontend",
        "CSS",
        "Database",
        "CMS",
        "Cloud",
        "Testing",
        "DevOps",
        "Animations",
        "Tools",
      ],
    };
  },
  computed: {
    currentTabComponent: function () {
      return this.currentTab;
    },
  },
};
</script>

<style scoped>
:root {
  --colorMain: #fa7070;
  --color2: #797687;
}

.corolMain {
  color: #fa7070;
}

.sec-2 p {
  color: #797687;
}

.btnDetails {
  border: 2px solid #fa7070;
  color: #fa7070;
  transition: 0.3s ease;
  box-shadow: 0 20px 30px 0 rgb(176 70 70 / 30%);
  -webkit-box-shadow: 0 20px 30px 0 rgb(176 70 70 / 30%);
}

.btnDetails:hover {
  color: white;
  background-color: #fa7070;
  transition: 0.3s ease;
}

.sec-3,
.sec-5,
.sec-7 {
  background: #f3f2ef !important;
}

.sec-3 img {
  width: 20px;
}

.sec-3 ul li {
  display: flex;
}

.sec-4 p {
  color: transparent;
}

.sec-4 .card {
  transition: 0.2s ease;
}

.sec-4 .card:hover {
  margin: -20px;
  transition: 0.2s ease;
}

.sec-4 .card:hover p {
  color: #797687;
  transition: 0.2s ease;
}

.sec-5 .card img {
  transition: 0.2s ease-in-out;
}

.sec-5 .card img:hover {
  transform: rotate(20deg);
  transition: 0.2s ease-in-out;
}

.tab-button {
  border: 2px solid #fa7070;
  color: #fa7070;
}

input{
      background: 0 0;
    border: 0;
    outline: 0;
    color: #fa7070;
    border-bottom: 1px solid #fa7070;
    padding: 15px 15px 15px 0;
    border-radius: 0;
    height: 60px;
    max-width: 500px;
    margin: 0;
    width: 100%;
}

::placeholder { /* Chrome, Firefox, Opera, Safari 10.1+ */
  color: #fa7070!important;
  opacity: 1; /* Firefox */
}

:-ms-input-placeholder { /* Internet Explorer 10-11 */
  color: #fa7070!important;
}

::-ms-input-placeholder { /* Microsoft Edge */
  color: #fa7070!important;
}
</style>
