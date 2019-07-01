<template>
  <main>
    <section class="container">
      <div class="section-inner flex flex-col items-center px-6">
        <div class="flex flex-col items-center text-center uppercase tracking-widest py-20">
          <h1 class="text-xl mb-4">Our Passion</h1>
          <h3 class="text-sm">simplify the complex</h3>
        </div>
        <img src="/img/ipad-peek-bottom.png" alt="Our Passion is Simple and Clean Design">
      </div>
    </section>

    <hr class="section-separator">

    <!-- Container -->
    <section class="container px-2">
      <!-- Row -->
      <div class="flex -mx-2">
        <!-- Column -->
        <div class="column w-1/2 px-2 flex items-center">
          <div
            class="flex-1 h-full flex flex-col justify-center text-center uppercase tracking-widest px-6 py-20 md:rounded-l"
            style="background-color:#e8e8e8;"
          >
            <h1 class="text-xl mb-20">Your Work is Beautiful</h1>
            <h3 class="text-sm">
              Let its quality shine through
              <br>with a simple website design
            </h3>
          </div>
        </div>

        <!-- Column with images -->
        <div class="column w-1/2 px-2">
          <div class="flex flex-wrap -mx-2">
            <div class="w-full lg:w-1/2 px-2 mb-4">
              <img
                class="w-full"
                src="img/interior-design-01.png"
                alt="Website design for interior designers"
              >
            </div>
            <div class="w-full lg:w-1/2 px-2 mb-4">
              <img
                class="w-full"
                src="img/interior-design-02.png"
                alt="Website design for interior designers"
              >
            </div>
            <div class="w-full lg:w-1/2 px-2 mb-4 lg:mb-0">
              <img
                class="w-full"
                src="img/interior-design-03.png"
                alt="Website design for interior designers"
              >
            </div>
            <div class="w-full lg:w-1/2 px-2">
              <img
                class="w-full"
                src="img/interior-design-04.png"
                alt="Website design for interior designers"
              >
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {};
</script>

<style lang="scss">
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
</style>
