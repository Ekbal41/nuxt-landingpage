<template>
  <header class="text-gray-600 body-font header-bg">
    <div
      class="
        container
        mx-auto
        flex flex-wrap
        p-5
        flex-col
        md:flex-row
        items-center
      "
    >
      <a
        class="
          flex
          title-font
          font-medium
          items-center
          text-gray-900
          mb-4
          md:mb-0
        "
      >
        <span class="ml-3 text-xl font-bold text-white">Apipy</span>
      </a>
      <nav
        class="
          md:mr-auto md:ml-4 md:py-1 md:pl-4 md:border-l md:border-white
          flex flex-wrap
          items-center
          text-base
          justify-center
        "
      >
        <a
          class="
            mr-5
            hover:text-green-500
            font-bold
            hover:bg-green-100
            text-white
            px-2
            py-1
            rounded
            transition-all
            cursor-pointer
          "
          >Home</a
        >
        <a
          class="
            mr-5
            hover:text-green-500
            font-bold
            hover:bg-green-100
            text-white
            px-2
            py-1
            rounded
            transition-all
            cursor-pointer
          "
          >Services</a
        >
      </nav>
      <button
        class="
          inline-flex
          items-center
          border-0
          py-1
          px-3
          focus:outline-none
          hover:bg-gray-200
          rounded
          text-green-500
          mt-4
          md:mt-0
          bg-white
        "
      >
        Register
        <svg
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          class="w-4 h-4 ml-1"
          viewBox="0 0 24 24"
        >
          <path d="M5 12h14M12 5l7 7-7 7"></path>
        </svg>
      </button>
    </div>
  </header>
</template>

<style scoped>
.header-bg {
  background-image: url('~/assets/img/flower.jpg');
}
</style>
