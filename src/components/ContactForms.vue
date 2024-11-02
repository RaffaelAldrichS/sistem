<template>
  <form
    action=""
    class="w-screen flex flex-col gap-2 py-8 mx-auto max-w-4xl lg:py-16"
  >
    <div class="w-full space">
      <input
        type="text"
        class="py-6 px-4 block w-full border border-[#6D6E7680] text-sm focus:border-blue-500 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-transparent dark:text-[#232536] dark:placeholder-[#232536]"
        placeholder="Full Name"
      />
    </div>
    <div class="w-full space">
      <input
        type="email"
        class="py-6 px-4 block w-full border border-[#6D6E7680] text-sm focus:border-blue-500 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-transparent dark:text-[#232536] dark:placeholder-[#232536]"
        placeholder="Your Email"
      />
    </div>
    <div class="w-full flex gap-4">
      <select
        class="py-6 px-4 block w-1/2 border border-[#6D6E7680] text-sm focus:border-blue-500 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-transparent dark:text-[#232536] dark:placeholder-[#232536]"
      >
        <option value="" disabled selected>Provinsi</option>
        <option value="">Jawa Tengah</option>
        <option value="">Jawa Timur</option>
        <option value="">Jawa Barat</option>
        <!-- Add your options here -->
      </select>
      <select
        class="py-6 px-4 block w-1/2 border border-[#6D6E7680] text-sm focus:border-blue-500 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-transparent dark:text-[#232536] dark:placeholder-[#232536]"
      >
        <option value="" disabled selected>Kota</option>
        <option value="">Surakarta</option>
        <option value="">Karanganyar</option>
        <option value="">Sukoharjo</option>
        <!-- Add your options here -->
      </select>
    </div>
    <div class="w-full space">
      <textarea
        class="py-6 px-4 block w-full border border-[#6D6E7680] text-sm focus:border-blue-500 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-transparent dark:text-[#232536] dark:placeholder-[#232536]"
        placeholder="Message"
        rows="4"
      ></textarea>
    </div>
    <button
      type="submit"
      class="py-6 px-4 block w-full bg-blue-500 text-white text-xl"
    >
      Send Message
    </button>
  </form>
</template>
