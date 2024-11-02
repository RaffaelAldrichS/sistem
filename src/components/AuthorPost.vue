<template>
  <div class="flex flex-col items-center w-full bg-gray-100 max-md:max-w-full">
    <section
      class="flex flex-col self-center my-16 w-full max-w-screen-lg max-md:mt-10 max-md:max-w-full p-8"
    >
      <h2
        class="self-start text-5xl font-bold tracking-tighter leading-none text-gray-800 max-md:text-4xl"
      >
        My Posts
      </h2>
      <div class="mt-16 max-md:mt-10 max-md:max-w-full">
        <div class="flex gap-5 max-md:flex-col">
          <div class="flex flex-col w-[42%] max-md:ml-0 max-md:w-full">
            <div class="flex flex-col grow max-md:mt-8">
              <img
                loading="lazy"
                src="https://cdn.builder.io/api/v1/image/assets/TEMP/7a0cfd0b5f4bac1070110b31f5611e8edaf3d046aecde01dc829c8565e0f4e88?placeholderIfAbsent=true&apiKey=9b496c92d7094d298e9ef9f44f40da42"
                alt="Blog post image 1"
                class="object-contain w-full aspect-[1.29]"
              />
              <img
                loading="lazy"
                src="https://cdn.builder.io/api/v1/image/assets/TEMP/c0b473980178f2522679e74bfb1e31f21a2fd33361b4681aac2dd2892843f79f?placeholderIfAbsent=true&apiKey=9b496c92d7094d298e9ef9f44f40da42"
                alt="Blog post image 2"
                class="object-contain mt-16 w-full aspect-[1.29] max-md:mt-10"
              />
            </div>
          </div>
          <div class="flex flex-col ml-5 w-[58%] max-md:ml-0 max-md:w-full">
            <div
              class="flex flex-col self-stretch my-auto text-base font-semibold leading-none text-amber-300 max-md:mt-10 max-md:max-w-full"
            >
              <span class="self-start uppercase tracking-[3px]">BUSINESS</span>
              <h3
                class="self-start mt-5 text-4xl font-bold tracking-tighter leading-10 text-gray-800 max-md:max-w-full"
              >
                Font sizes in UI design: The complete guide to follow
              </h3>
              <p class="mt-4 leading-7 text-zinc-500 max-md:max-w-full">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
              <span
                class="self-start mt-44 uppercase tracking-[3px] max-md:mt-10"
                >ECONOMY</span
              >
              <h3
                class="mt-5 mr-5 text-4xl font-bold tracking-tighter leading-10 text-gray-800 max-md:mr-2.5 max-md:max-w-full"
              >
                How to build rapport with your web design clients
              </h3>
              <p class="mt-4 leading-7 text-zinc-500 max-md:max-w-full">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
