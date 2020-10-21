<template>
  <div class="pt-0 text-black">
    <main>
      <section>
        <div
          class="container px-3 mx-auto flex flex-wrap flex-col md:flex-row items-center"
        >
          <!--Left Col-->
          <div
            class="flex flex-col w-full md:w-2/5 justify-center items-start text-center md:text-left"
          >
            <p class="uppercase tracking-loose w-full">
              Want to be verified?
            </p>
            <h1 class="my-4 text-5xl font-bold leading-tight">
              Simplest way to get verified
            </h1>
            <p class="leading-normal text-xl mb-8">
              we use your bvn in giving you a fast verification no cap 😎
            </p>

            <div
              class="flex md:flex-no-wrap flex-wrap justify-center md:justify-start"
            >
              <input
                class="sm:w-64 w-40 bg-gray-300 rounded sm:mr-4 mr-2 border border-gray-400 focus:outline-none focus:border-indigo-500 text-base py-2 px-4"
                placeholder="eg 20123456"
                type="text"
              />
              <button
                class="inline-flex text-white   py-2 px-6 focus:outline-none rounded btn"
              >
                Send
              </button>
            
            </div>
          </div>
          <!--Right Col-->
          <div class="w-full md:w-3/5 py-6 text-center">
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
