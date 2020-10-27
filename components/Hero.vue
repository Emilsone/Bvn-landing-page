<template>
  <div class="pt-0 text-black">
    <main>


      <section class="text-gray-700 body-font">
        <div
          class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center"
        >
          <div
            class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
          >
            <p class="capitalize  text-sm w-full">
              Want to be verified?
            </p>
            <h1
              class="title-font sm:text-5xl text-4xl mb-4 font-bold text-gray-900 "
            >
              Simplest way to get verified
            </h1>
            <p class="mb-8 leading-relaxed text-lg">
              we use your bvn in giving you a fast verification no cap 😎
            </p>
            <div class="flex w-full md:justify-start justify-center">
              <input
                class="bg-gray-100 rounded mr-4 border border-gray-400 focus:outline-none focus:border-indigo-500 text-base px-4 lg:w-full xl:w-1/2 w-2/4 md:w-full"
                placeholder="2015678349"
                type="text"
              />
              <button
                class="inline-flex text-white  py-2 px-6 focus:outline-none  rounded text-lg btn"
              >
                Send
              </button>
            </div>
          </div>
          <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
            <img
              class="w-full md:w-4/5 z-50"
              src="~/assets/img/mobile-img.png"
              alt
            />
          </div>
        </div>
      </section>
    </main>
  </div>
</template>

<script>
export default {
  name: 'Hero'
}
</script>
