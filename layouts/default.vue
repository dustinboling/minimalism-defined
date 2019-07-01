<template>
  <div class="border-t-4 border-black">
    <header class="border-t-8" style="border-color:#e8e8e8;">
      <nav class="container mx-auto flex items-center justify-between flex-wrap py-12 px-6 md:px-0">
        <div class="flex flex-col flex-shrink-0 mr-6">
          <nuxt-link class="uppercase text-xl tracking-widest mb-0" to="/">
            Minimalism
            <span class="font-light">Defined</span>
          </nuxt-link>
          <p
            class="text-xs uppercase tracking-widest text-gray-600"
          >Custom website design &amp; development</p>
        </div>

        <div class="block lg:hidden">
          <button
            class="flex items-center px-3 py-2 border rounded-sm text-gray-200 border-gray-400 hover:text-white hover:border-white"
          >
            <svg
              class="fill-current h-3 w-3"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <title>Menu</title>
              <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
            </svg>
          </button>
        </div>

        <div class="w-full block flex-grow lg:flex lg:items-center lg:justify-end lg:w-auto">
          <div class="uppercase tracking-widest text-xs">
            <nuxt-link
              to="/our-passion"
              class="block mt-4 lg:inline-block lg:mt-0 hover:text-gray-500 mr-4"
            >Our Passion</nuxt-link>
            <nuxt-link
              to="/our-process"
              class="block mt-4 lg:inline-block lg:mt-0 hover:text-gray-500 mr-4"
            >Our Process</nuxt-link>
          </div>

          <div>
            <nuxt-link
              to="/request-proposal"
              class="btn btn-white hover:border-transparent hover:text-white hover:bg-black mt-4 lg:mt-0"
            >Request a Proposal</nuxt-link>
          </div>
        </div>
      </nav>
    </header>
    <nuxt/>

    <hr class="section-separator">

    <aside class="container px-2">
      <div
        class="flex items-center justify-between h-32 shadow rounded"
        style="background-color:#e8e8e8;"
      >
        <h3 class="mx-auto uppercase tracking-widest">How can we help you today?</h3>
        <nuxt-link
          class="mx-auto btn btn-white focus:outline-none focus:shadow-outline"
          to="/contact-us"
        >I Need Minor Modifications</nuxt-link>
        <nuxt-link
          class="mx-auto btn btn-white focus:outline-none focus:shadow-outline"
          to="/contact-us"
        >Refresh My Existing Website</nuxt-link>
        <nuxt-link
          class="mx-auto btn btn-black focus:outline-none focus:shadow-outline"
          style="background-color:#2CC0D6"
          to="/contact-us"
        >Create a New Website</nuxt-link>
      </div>
    </aside>
    <footer class="flex items-center justify-around py-12">
      <span
        class="text-xs text-gray-400 uppercase tracking-widest"
      >&copy;2019 Minimalism Defined. All rights reserved.</span>
    </footer>
  </div>
</template>

<style lang="scss">
html {
  font-family: futura-pt, "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS",
    sans-serif;
  color: #222;
}
p {
  font-weight: 300;
  letter-spacing: 0.03em;
}
hr.section-separator {
  border-color: #e8e8e8;
  @apply w-1/6 mx-auto my-12 border-dashed border-2;
}
.container {
  @apply mx-auto;
}
section.container {
  .section-inner {
    background-color: #e8e8e8;
    @apply rounded shadow;
  }
  .img-wrap {
    @apply py-3;
  }
}
.btn {
  @apply inline-block uppercase tracking-widest text-xs px-5 py-3 leading-none text-xs rounded-sm;
}
.btn-black {
  @apply text-white bg-black;
}
.btn-white {
  @apply text-black bg-white border border-gray-500;
}
</style>
