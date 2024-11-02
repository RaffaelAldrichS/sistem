<!-- Testimonial.vue -->
<template>
  <div
    class="bg-[#FDF6EC] flex items-center justify-center py-10 lg:py-16 mx-auto max-w-screen-xl px-4 my-16"
  >
    <div class="max-w-6xl w-full">
      <div class="grid md:grid-cols-2 gap-8 items-start">
        <!-- Left Section -->
        <div class="space-y-4 border-r-2 border-gray-400">
          <h3 class="uppercase text-sm font-medium tracking-wider">
            Testimonials
          </h3>
          <h2 class="text-3xl md:text-4xl font-bold text-gray-900">
            What people say about our blog
          </h2>
          <p class="text-gray-600 text-xl">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor.
          </p>
        </div>

        <!-- Right Section -->
        <div class="space-y-8">
          <p class="text-gray-800 text-2xl mb-16 font-bold">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>

          <!-- Author Section -->
          <div class="flex items-center justify-between">
            <div class="flex items-center gap-4">
              <img
                src="/img/Author1.png"
                alt="Profile"
                class="w-12 h-12 rounded-full"
              />
              <div>
                <h4 class="font-semibold text-gray-900">Jonathan Vallem</h4>
                <p class="text-gray-500">New york, USA</p>
              </div>
            </div>

            <!-- Navigation Buttons -->
            <div class="flex gap-4">
              <button
                class="p-4 rounded-full border border-gray-200 bg-white hover:bg-gray-800 hover:"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M15 19l-7-7 7-7"
                  />
                </svg>
              </button>
              <button
                class="p-4 rounded-full border border-gray-200 bg-white hover:bg-gray-800 hover:"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M9 5l7 7-7 7"
                  />
                </svg>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TestimonialSection",
};
</script>
