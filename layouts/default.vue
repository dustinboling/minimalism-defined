<template>
  <div>
    <header>
        <nav class="container mx-auto flex items-center justify-between flex-wrap py-12">

            <div class="flex items-center flex-shrink-0 mr-6">
                <nuxt-link class="uppercase text-xl tracking-widest" to="/">Minimalism <span class="font-light">Defined</span></nuxt-link>
            </div>

            <div class="block lg:hidden">
                <button class="flex items-center px-3 py-2 border rounded-sm text-gray-200 border-gray-400 hover:text-white hover:border-white">
                    <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
                </button>
            </div>

            <div class="w-full block flex-grow lg:flex lg:items-center lg:justify-end lg:w-auto">

                <div class="uppercase tracking-widest text-xs">
                    <nuxt-link to="/our-passion" class="block mt-4 lg:inline-block lg:mt-0 hover:text-gray-500 mr-4">
                        Our Passion
                    </nuxt-link>
                    <nuxt-link to="/our-process" class="block mt-4 lg:inline-block lg:mt-0 hover:text-gray-500 mr-4">
                        Our Process
                    </nuxt-link>
                </div>

                <div>
                    <nuxt-link to="/request-proposal" class="btn btn-white hover:border-transparent hover:text-white hover:bg-black mt-4 lg:mt-0">Request a Proposal</nuxt-link>
                </div>

            </div>

        </nav>
    </header>
    <nuxt />
    <footer class="flex items-center justify-around py-8">
      <span class="text-xs text-gray-400 uppercase tracking-widest">&copy;2019 Minimalism Defined. All rights reserved.</span>
    </footer>
  </div>
</template>

<style>
html {
    font-family: futura-pt, 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: #222;
}
p {
    font-weight: 300;
    letter-spacing: 0.03em;
}
.container {
  @apply mx-auto;
}
section.container {
  @apply mb-20;
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
