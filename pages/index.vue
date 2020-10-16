<template>
  <section class="flex flex-col mt-16 space-y-6">
    <!-- Hero -->
    <div class="px-16">
      <div class="flex flex-wrap items-center">
        <div class="flex flex-wrap items-center w-1/2 h-128">
          <div class="flex flex-col space-y-10">
            <h1
              class="font-extrabold leading-tight font-primary text-display-4"
            >
              Welcome to the
              <br />
              Qloud Apps
              <span class="text-blue">Universe</span>
            </h1>
            <p class="text-subtitle-1 text-gray-light">
              Tailwindow is a collection of UI Components created using Tailwind
              CSS Framework. The UI Components gives you all of the building
              blocks you need to build any designs without any annoying
              opinionated styles you have to fight to override.
            </p>
            <div class="flex flex-wrap space-x-8">
              <button
                class="flex items-center justify-between h-12 px-4 text-white transition duration-500 text-title-3 bg-blue rounded-10 focus:outline-none hover:bg-blue-hover"
              >
                Introduction
                <svg
                  class="w-6 h-6 ml-12"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
              </button>
              <button
                class="flex items-center justify-center h-12 px-4 transition duration-500 border-2 text-blue text-title-3 border-blue rounded-10 focus:outline-none hover:bg-blue-hover hover:border-blue-hover hover:text-white"
              >
                Read Documentation
              </button>
            </div>
          </div>
        </div>
        <div class="w-1/2 p-10">
          <div class="flex items-center mb-5">
            <div class="w-4/12 px-3 space-y-6">
              <div v-scroll-reveal="{ delay: 200 }">
                <div
                  class="block p-5 my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 rounded shadow-10 hover:scale-95"
                  style="
                    background: url(https://images.ui8.net/uploads/stylesheets_ui81x_1588845572222.jpg)
                      center;
                    background-size: cover;
                  "
                >
                  <div class="h-32"></div>
                </div>
              </div>

              <div v-scroll-reveal="{ delay: 300 }">
                <div
                  class="block p-5 my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 rounded shadow-10 hover:scale-95"
                  style="
                    background: url(https://images.ui8.net/uploads/responsive_ui81x_1588845625844.jpg)
                      center;
                    background-size: cover;
                  "
                >
                  <div class="h-48"></div>
                </div>
              </div>

              <div v-scroll-reveal="{ delay: 400 }">
                <div
                  class="block p-5 my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 rounded shadow-b-10 hover:scale-95"
                  style="
                    background: url(https://images.ui8.net/uploads/intro_ui81x_1588845552361.jpg)
                      center;
                    background-size: cover;
                  "
                >
                  <div class="h-24"></div>
                </div>
              </div>
            </div>
            <div class="w-8/12 px-3 space-y-6">
              <div v-scroll-reveal="{ delay: 600 }">
                <div
                  class="block my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 bg-white rounded-lg shadow-10 hover:scale-95"
                >
                  <img
                    height="350"
                    src="https://qloud-storage.s3-ap-southeast-1.amazonaws.com/images/bigsur/01.png"
                    alt=""
                  />
                </div>
              </div>

              <div v-scroll-reveal="{ delay: 500 }">
                <div
                  class="block my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 bg-white rounded shadow-10 hover:scale-95"
                >
                  <img
                    height="350"
                    src="https://qloud-storage.s3-ap-southeast-1.amazonaws.com/images/bigsur/03.png"
                    alt=""
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Client -->
    <div class="flex flex-col items-center justify-center space-y-12">
      <h2>INNOVATIVE BUSINESSES TRUST DIGITALOCEAN</h2>
      <div class="flex flex-wrap space-x-8">
        <img
          src="https://prismic-io.s3.amazonaws.com/www-static/591cf605-46aa-4a7b-8af5-90036c252c97_docker-bab60eeb.svg"
          alt=""
        />
        <img
          src="https://prismic-io.s3.amazonaws.com/www-static/da244a8e-2546-47b1-aae2-b9824c657708_gitlab-166e2067.svg"
          alt=""
        />
        <img
          src="https://prismic-io.s3.amazonaws.com/www-static/b3f152c0-5465-45ba-80ab-2cdd258e6bee_slack-e20293da.svg"
          alt=""
        />
        <img
          src="https://prismic-io.s3.amazonaws.com/www-static/9351f07e-afbc-439a-a75f-3eca82be9c0e_hashicorp-4431df79.svg"
          alt=""
        />
        <img
          src="https://prismic-io.s3.amazonaws.com/www-static/01ff74d1-79dd-4f18-888f-4a93a976e61d_wework-be6eab32.svg"
          alt=""
        />
        <img
          src="https://prismic-io.s3.amazonaws.com/www-static/1583c145-22f8-402c-96f8-3af919a0df25_splunklogo.svg"
          alt=""
        />
      </div>
    </div>

    <!-- Opening -->
    <div class="text-gray-700 body-font bg-blue">
      <div
        class="container flex flex-col items-center h-screen px-5 py-24 mx-auto md:flex-row"
      >
        <div
          class="flex flex-col items-center mb-16 text-center lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 md:items-start md:text-left md:mb-0"
        >
          <h1
            v-scroll-reveal="{ delay: 100 }"
            class="mb-4 font-bold leading-snug text-white font-primary text-display-5"
          >
            Qloud POS
          </h1>
          <p
            v-scroll-reveal="{ delay: 200 }"
            class="mb-8 text-lg font-light leading-relaxed text-white"
          >
            Lorem Ipsum adalah contoh teks atau dummy dalam industri percetakan
            dan penataan huruf atau typesetting. Lorem Ipsum telah menjadi
            standar contoh teks sejak tahun 1500an, saat seorang tukang cetak
            yang tidak dikenal mengambil sebuah kumpulan teks dan mengacaknya
            untuk menjadi sebuah buku contoh huruf. Ia tidak hanya bertahan
            selama 5 abad
          </p>
        </div>
        <div class="w-1/2 w-full md:w-1/2">
          <div class="flex items-center mb-5">
            <div class="w-4/12 px-3 space-y-6">
              <div v-scroll-reveal="{ delay: 500 }">
                <div
                  class="block p-5 my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 rounded hover:scale-95"
                  style="
                    background: url(https://images.unsplash.com/photo-1531537571171-a707bf2683da?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=967&q=80)
                      center;
                    background-size: cover;
                  "
                >
                  <div class="h-32"></div>
                </div>
              </div>

              <div v-scroll-reveal="{ delay: 600 }">
                <div
                  class="block p-5 my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 rounded hover:scale-95"
                  style="
                    background: url(https://images.unsplash.com/photo-1531493731235-b5c309dca387?ixlib=rb-1.2.1&auto=format&fit=crop&w=1267&q=80)
                      center;
                    background-size: cover;
                  "
                >
                  <div class="h-48"></div>
                </div>
              </div>

              <div v-scroll-reveal="{ delay: 700 }">
                <div
                  class="block p-5 my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 rounded hover:scale-95"
                  style="
                    background: url(https://images.unsplash.com/photo-1531538606174-0f90ff5dce83?ixlib=rb-1.2.1&auto=format&fit=crop&w=1267&q=80)
                      center;
                    background-size: cover;
                  "
                >
                  <div class="h-24"></div>
                </div>
              </div>
            </div>
            <div class="w-8/12 px-3 space-y-6">
              <div v-scroll-reveal="{ delay: 800 }">
                <div
                  class="block my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 bg-white rounded-lg shadow-2xl hover:scale-95"
                >
                  <img
                    src="https://images.unsplash.com/photo-1531538512164-e6c51ea63d20?ixlib=rb-1.2.1&auto=format&fit=crop&w=1267&q=80"
                    alt=""
                  />
                </div>
              </div>

              <div v-scroll-reveal="{ delay: 900 }">
                <div
                  class="block my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 rounded shadow-2xl hover:scale-95"
                >
                  <img
                    src="https://images.unsplash.com/photo-1531497865144-0464ef8fb9a9?ixlib=rb-1.2.1&auto=format&fit=crop&w=1267&q=80"
                    alt=""
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Product -->
    <div class="flex flex-wrap px-2">
      <div class="w-1/2 p-2">
        <div class="flex flex-col items-center justify-center p-4 bg-light">
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
        <div class="flex flex-col items-center justify-center p-4 bg-light">
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

    <div class="text-gray-700 bg-black">
      <div
        class="container flex flex-col items-center h-screen px-5 py-24 mx-auto md:flex-row"
      >
        <div
          class="flex flex-col items-center mb-16 space-y-6 text-center lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 md:items-start md:text-left md:mb-0"
        >
          <div class="flex flex-wrap space-x-6">
            <img
              class="h-20"
              src="https://qloud-storage.s3-ap-southeast-1.amazonaws.com/logo/qloud-x.svg"
              alt=""
            />
            <img
              class="h-20"
              src="https://qloud-website.s3-ap-southeast-1.amazonaws.com/c/kineticx/logo/kineticx-logo.png"
              alt=""
            />
          </div>
          <h1
            v-scroll-reveal="{ delay: 100 }"
            class="mb-4 font-bold leading-snug text-white font-primary text-display-5"
          >
            Sport Science Apps for KineticX
          </h1>
          <p v-scroll-reveal="{ delay: 200 }" class="text-grey">
            Lorem Ipsum adalah contoh teks atau dummy dalam industri percetakan
            dan penataan huruf atau typesetting. Lorem Ipsum telah menjadi
            standar contoh teks sejak tahun 1500an, saat seorang tukang cetak
            yang tidak dikenal mengambil sebuah kumpulan teks dan mengacaknya
            untuk menjadi sebuah buku contoh huruf. Ia tidak hanya bertahan
            selama 5 abad
          </p>
        </div>
        <div class="w-1/2 w-full md:w-1/2">
          <div class="flex items-center mb-5">
            <div class="w-4/12 px-3 space-y-6">
              <div v-scroll-reveal="{ delay: 500 }">
                <div
                  class="block p-5 my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 rounded hover:scale-95"
                  style="
                    background: url(https://qloud-website.s3-ap-southeast-1.amazonaws.com/c/kineticx/general/evaluate.jpg)
                      center;
                    background-size: cover;
                  "
                >
                  <div class="h-32"></div>
                </div>
              </div>

              <div v-scroll-reveal="{ delay: 600 }">
                <div
                  class="block p-5 my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 rounded hover:scale-95"
                  style="
                    background: url(https://images.unsplash.com/photo-1531493731235-b5c309dca387?ixlib=rb-1.2.1&auto=format&fit=crop&w=1267&q=80)
                      center;
                    background-size: cover;
                  "
                >
                  <div class="h-48"></div>
                </div>
              </div>

              <div v-scroll-reveal="{ delay: 700 }">
                <div
                  class="block p-5 my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 rounded hover:scale-95"
                  style="
                    background: url(https://qloud-website.s3-ap-southeast-1.amazonaws.com/c/kineticx/products/force-frame/IMG_4794.JPG)
                      center;
                    background-size: cover;
                  "
                >
                  <div class="h-24"></div>
                </div>
              </div>
            </div>
            <div class="w-8/12 px-3 space-y-6">
              <div v-scroll-reveal="{ delay: 800 }">
                <div
                  class="block my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 bg-white rounded-lg shadow-2xl hover:scale-95"
                >
                  <img
                    src="https://qloud-website.s3-ap-southeast-1.amazonaws.com/c/kineticx/services/evaluate/image-4.jpg"
                    alt=""
                  />
                </div>
              </div>

              <div v-scroll-reveal="{ delay: 900 }">
                <div
                  class="block my-3 mb-2 overflow-hidden transition-all duration-500 transform scale-100 rounded shadow-2xl hover:scale-95"
                >
                  <img
                    src="https://qloud-website.s3-ap-southeast-1.amazonaws.com/c/kineticx/products/decks/IMG_4820.jpg"
                    alt=""
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- QloudX -->

    <footer class="text-white border-t border-light">
      <div>
        <div
          class="container flex flex-col flex-wrap px-5 py-4 mx-auto sm:flex-row"
        >
          <p class="text-sm text-center text-gray-500 sm:text-left">
            © 2020 Qloud ID —
            <a
              href="#"
              rel="noopener noreferrer"
              class="ml-1 text-gray-600"
              target="_blank"
              >@ Surabaya</a
            >
          </p>
          <span
            class="inline-flex justify-center mt-2 sm:ml-auto sm:mt-0 sm:justify-start"
          >
            <a class="text-gray-500">
              <svg
                fill="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-5 h-5"
                viewBox="0 0 24 24"
              >
                <path
                  d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"
                ></path>
              </svg>
            </a>
            <a class="ml-3 text-gray-500">
              <svg
                fill="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-5 h-5"
                viewBox="0 0 24 24"
              >
                <path
                  d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"
                ></path>
              </svg>
            </a>
            <a class="ml-3 text-gray-500">
              <svg
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                class="w-5 h-5"
                viewBox="0 0 24 24"
              >
                <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                <path
                  d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"
                ></path>
              </svg>
            </a>
            <a class="ml-3 text-gray-500">
              <svg
                fill="currentColor"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="0"
                class="w-5 h-5"
                viewBox="0 0 24 24"
              >
                <path
                  stroke="none"
                  d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"
                ></path>
                <circle cx="4" cy="4" r="2" stroke="none"></circle>
              </svg>
            </a>
          </span>
        </div>
      </div>
    </footer>
  </section>
</template>

<script>
export default {}
</script>

<style></style>
