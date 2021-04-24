<template>
  <nav class="flex flex-col justify-center fixed w-full h-24 top-nav">
    <div class="mx-10 md:mx-40 flex items-center justify-between">
      <a href="#">
        <img
          src="https://devxhub.com/storage/uploads/logos/1617479508-x-devxhub-next-logo.png"
          alt=""
        />
      </a>

      <div>
        <ul class="flex space-x-16 text-xl">
          <li>Home</li>
          <li>
            <span>Company</span>
            <div class="dropdown-content p-2 space-y-4 text-lg">
              <a href="#">Link 1</a>
              <a href="#">Link 2</a>
              <a href="#">Link 3</a>
            </div>
          </li>
          <li class="service">
            <span>services</span>
            <div class="dropdown-content p-2 space-y-4 text-lg w-2/4">
              <div class="grid grid-cols-3 gap-6">
                <div>
                  <a href="#">Link 1</a>
                  <a href="#">Link 2</a>
                  <a href="#">Link 3</a>
                </div>
                <div>
                  <a href="#">Link 1</a>
                  <a href="#">Link 2</a>
                  <a href="#">Link 3</a>
                </div>
                <div>
                  <a href="#">Link 1</a>
                  <a href="#">Link 2</a>
                  <a href="#">Link 3</a>
                </div>
              </div>
            </div>
          </li>
          <li>How we Work</li>
          <li>Contact</li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavbarBrand",
};
</script>

<style scoped>
nav {
  z-index: 100;
  color: white;
}

.top-nav {
  background: #000000;
}

ul li:hover {
  cursor: pointer;
}

.dropdown-content {
  display: none;
  position: absolute;
  background: linear-gradient(
    135deg,
    #fff 30%,
    #ffefe0 56%,
    #fff 83%,
    #fff
  ) !important;
  border-top: 10px solid #f3b92e !important;
  min-width: 250px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
  transform: translate(-25%, 0);
}

.service .dropdown-content {
  transform: translate(-50%, 0);
}

.dropdown-content a {
  color: black;
  padding: 4px 8px;
  text-decoration: none;
  display: block;
  border-radius: 2px;
}

.dropdown-content a:hover {
  background-image: linear-gradient(100deg, #fa7070, #fa9770);
  color: #fff;
}

li:hover .dropdown-content {
  display: block;
}
</style>
