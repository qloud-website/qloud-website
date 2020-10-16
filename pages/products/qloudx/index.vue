<template>
  <div class="container mx-auto mt-24">
    <h1 class="font-bold font-primary text-heading-1">ini halaman customer</h1>

    <!-- Product -->
    <div class="flex flex-wrap px-2">
      <div class="w-1/2 p-2">
        <div
          v-scroll-reveal="{ delay: 100 }"
          class="flex flex-col items-center justify-center p-4 bg-light"
        >
          <div class="flex flex-col items-center justify-center my-8">
            <p class="text-gray text-title-4">Qloud Business</p>
            <h1 class="font-extrabold leading-none text-heading-1 font-primary">
              Explorer Qloud HR
            </h1>
            <p class="mt-4 text-center">
              Pay for your new Mac over 12 months, <br />
              interest‑free with Apple Card.
            </p>
            <nuxt-link to="/hr" class="mt-2 text-blue"
              >Selengkapnya ></nuxt-link
            >
          </div>
          <img src="/image/hr.png" alt="" />
        </div>
      </div>
      <div class="w-1/2 p-2">
        <div
          v-scroll-reveal="{ delay: 200 }"
          class="flex flex-col items-center justify-center p-4 bg-light"
        >
          <div class="flex flex-col items-center justify-center my-8">
            <p class="text-gray text-title-4">Qloud Business</p>
            <h1 class="font-extrabold leading-none text-heading-1 font-primary">
              Explorer Qloud Sales
            </h1>
            <p class="mt-4 text-center">
              Pay for your new Mac over 12 months, <br />
              interest‑free with Apple Card.
            </p>
            <nuxt-link to="/hr" class="mt-2 text-blue"
              >Selengkapnya ></nuxt-link
            >
          </div>
          <img src="/image/sales.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
