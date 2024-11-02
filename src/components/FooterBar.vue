<script setup>
import { Facebook, Instagram, Linkedin, Twitter } from "lucide-vue-next";
import Logo from "/img/Logo.png";
import ButtonView from "@/components/ButtonView.vue";
</script>
<template>
  <!-- ========== FOOTER ========== -->
  <footer class="mt-auto bg-[#232536]">
    <div class="w-full max-w-screen-xl mx-auto p-4 md:py-8">
      <div class="flex flex-col sm:flex-row sm:items-center sm:justify-between">
        <RouterLink
          to="https://flowbite.com/"
          class="flex items-center mb-4 sm:mb-0 space-x-3 rtl:space-x-reverse"
        >
          <img :src="Logo" class="h-6" alt="Flowbite Logo" />
        </RouterLink>
        <ul
          class="flex flex-col sm:flex-row flex-wrap items-center mb-6 text-md font-light text-white sm:mb-0"
        >
          <li class="mb-2 sm:mb-0">
            <RouterLink to="/" class="hover:underline me-4 md:me-6"
              >Home</RouterLink
            >
          </li>
          <li class="mb-2 sm:mb-0">
            <RouterLink to="/blog" class="hover:underline me-4 md:me-6"
              >Blog</RouterLink
            >
          </li>
          <li class="mb-2 sm:mb-0">
            <RouterLink to="/about" class="hover:underline me-4 md:me-6"
              >About Us</RouterLink
            >
          </li>
          <li class="mb-2 sm:mb-0">
            <RouterLink to="/contact" class="hover:underline me-4 md:me-6"
              >Contact Us</RouterLink
            >
          </li>
          <li>
            <RouterLink to="/privacyPolicy" class="hover:underline"
              >Privacy Policy</RouterLink
            >
          </li>
        </ul>
      </div>
      <!-- Subscribe -->
      <div class="bg-gray-700 px-6 py-8 sm:px-8 lg:px-10 my-8 lg:py-20 mx-auto">
        <div class="grid md:grid-cols-2 gap-8">
          <div class="max-w-md">
            <h2
              class="text-2xl font-bold md:text-3xl md:leading-normal dark:text-white"
            >
              Subscribe to our news letter to get latest updates and news
            </h2>
          </div>

          <form>
            <div class="w-full sm:max-w-lg md:ms-auto">
              <div
                class="flex flex-col items-center gap-2 sm:flex-row sm:gap-3"
              >
                <div class="w-full">
                  <label for="hero-input" class="sr-only">Search</label>
                  <input
                    type="text"
                    id="hero-input"
                    name="hero-input"
                    class="py-3 px-4 block w-full border border-gray-500 rounded-md text-sm focus:border-blue-500 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-transparent dark:text-neutral-400 dark:placeholder-neutral-500"
                    placeholder="Enter Your Email"
                  />
                </div>
                <ButtonView label="Subscribe" :icon="false" />
              </div>
            </div>
          </form>
        </div>
      </div>
      <!-- End Subscribe -->
      <div
        class="mt-5 sm:mt-12 grid gap-y-2 sm:gap-y-0 sm:flex sm:justify-between sm:items-center"
      >
        <div class="flex flex-col justify-between">
          <p class="text-md text-gray-400 dark:text-neutral-400">
            Finstreet 118 2561 Fintown
          </p>
          <p class="text-md text-gray-400 dark:text-neutral-400">
            Hello@finsweet.com 020 7993 2905
          </p>
        </div>
        <!-- End Col -->

        <!-- Social Brands -->
        <div class="flex justify-center space-x-4 mt-4 sm:mt-0">
          <a
            class="size-10 inline-flex justify-center items-center gap-x-2 text-sm font-semibold rounded-lg border border-transparent text-white hover:bg-white/10 focus:outline-none focus:bg-white/10 disabled:opacity-50 disabled:pointer-events-none"
            href="#"
          >
            <Facebook size="20" />
          </a>
          <a
            class="size-10 inline-flex justify-center items-center gap-x-2 text-sm font-semibold rounded-lg border border-transparent text-white hover:bg-white/10 focus:outline-none focus:bg-white/10 disabled:opacity-50 disabled:pointer-events-none"
            href="#"
          >
            <Twitter size="20" />
          </a>
          <a
            class="size-10 inline-flex justify-center items-center gap-x-2 text-sm font-semibold rounded-lg border border-transparent text-white hover:bg-white/10 focus:outline-none focus:bg-white/10 disabled:opacity-50 disabled:pointer-events-none"
            href="#"
          >
            <Instagram size="20" />
          </a>
          <a
            class="size-10 inline-flex justify-center items-center gap-x-2 text-sm font-semibold rounded-lg border border-transparent text-white hover:bg-white/10 focus:outline-none focus:bg-white/10 disabled:opacity-50 disabled:pointer-events-none"
            href="#"
          >
            <Linkedin size="20" />
          </a>
        </div>
      </div>
    </div>

    <!-- End Social Brands -->
  </footer>
  <!-- ========== END FOOTER ========== -->
</template>
