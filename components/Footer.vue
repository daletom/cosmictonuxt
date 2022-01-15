<template>
  <div>
    <div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:py-16 lg:px-8">
      <div class="lg:grid lg:grid-cols-2 lg:gap-8 lg:items-center">
        <div>
          <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
            Let's Go Headless Tutorial
          </h2>
          <p class="mt-3 max-w-3xl text-lg text-gray-500">
            Let's Go Headless is an informational and tutorial website about Headless Web Architecture.  This site is a demo site from a Cosmic to Nuxt.js tutorial.
          </p>
          <div class="mt-8 sm:flex">
            <div class="rounded-md shadow">
              <a href="https://www.letsgoheadless.com/article/cosmictonuxt" class="flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-white buttonbg1">
                See Tutorial
              </a>
            </div>
            <div class="mt-3 sm:mt-0 sm:ml-3">
              <a href="https://www.letsgoheadless.com/" class="flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-white buttonbg2">
                Let's Go Headless
              </a>
            </div>
          </div>
        </div>
        <div class="mt-8 grid grid-cols-2 gap-0.5 md:grid-cols-3 lg:mt-0 lg:grid-cols-2">
          <div class="col-span-1 flex justify-center py-8 px-8">
            <img src="https://tom.imgix.net/letsgoheadless_logo_mobile.png?auto=format,compress&w=300" alt="Let's Go Headless Logo" />
          </div>
          <div class="col-span-1 flex justify-center py-8 px-8">
            <img src="https://tom.imgix.net/cosmictonuxt_tutorial.png?auto=format,compress&w=300" alt="Cosmic to Nuxt Tutorial Logo" />
          </div>
          
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.footer {
  padding: 40px 0;
  max-width: 700px;
  margin: 0 auto;
  text-align: center;
  border-top: 1px solid #DADADA;
  }

.logo {
  width: 300px
  }

.buttonbg1 {
  background-color: #214B91;
  }

.buttonbg1:hover {
    background-color: #F25827;
}

.buttonbg2:hover {
  background-color: #214B91;
  }

.buttonbg2 {
    background-color: #F25827;
}

</style>