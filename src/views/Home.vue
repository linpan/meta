<template>
  <div class="tw-h-screen tw-flex tw-flex-col tw-mx-auto tw-justify-between">
    <div class="header tw-w-full tw-h-16 tw-flex tw-justify-between tw-px-2 tw-items-center tw-px-4 tw-border-b tw-border-gray-200 tw-border-opacity-80 tw-shadow">
      <div class="return-icon">
        <svg xmlns="http://www.w3.org/2000/svg" class="tw-h-5 tw-w-5" viewBox="0 0 20 20" fill="currentColor">
          <path fillRule="evenodd" d="M9.707 16.707a1 1 0 01-1.414 0l-6-6a1 1 0 010-1.414l6-6a1 1 0 011.414 1.414L5.414 9H17a1 1 0 110 2H5.414l4.293 4.293a1 1 0 010 1.414z" clipRule="evenodd" />
        </svg>
      </div>
      <div class="tw-flex-1 tw-text-center">10月29 早起来(3)</div>
      <div class="more-dots">
        <svg xmlns="http://www.w3.org/2000/svg" class="tw-h-5 tw-w-5" viewBox="0 0 20 20" fill="currentColor">
          <path d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z" />
        </svg>
      </div>
    </div>
    <div class="tw-flex-1 tw-bg-yellow-200 tw-overflow-y-auto">
      <h3 class="tw-my-32" v-for="n of 33" :key="n"> linpan</h3>
    </div>
    <div class="footer-input  tw-w-full tw-bg-red-300">
      <div class="tw-flex tw-justify-between tw-items-center">
        <div class="">
          <button type="button" class="tw-inline-flex tw-items-center tw-justify-center tw-rounded-full tw-h-12 tw-w-12 tw-transition tw-duration-500 tw-ease-in-out tw-text-gray-500 hover:tw-bg-gray-300 focus:tw-outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="tw-h-6 tw-w-6 tw-text-gray-600">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11a7 7 0 01-7 7m0 0a7 7 0 01-7-7m7 7v4m0 0H8m4 0h4m-4-8a3 3 0 01-3-3V5a3 3 0 116 0v6a3 3 0 01-3 3z"></path>
            </svg>
          </button>
        </div>
        <input type="text" placeholder="Write" class="w-full focus:tw-outline-none focus:tw-placeholder-gray-400 tw-bg-blue-500">
        <div>
          <button type="button" class="tw-inline-flex tw-items-center tw-justify-center tw-rounded-full tw-h-10 tw-w-10 tw-transition tw-duration-500 tw-ease-in-out tw-text-gray-500 hover:tw-bg-gray-300 focus:tw-outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="tw-h-6 tw-w-6 tw-text-gray-600">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.172 7l-6.586 6.586a2 2 0 102.828 2.828l6.414-6.586a4 4 0 00-5.656-5.656l-6.415 6.585a6 6 0 108.486 8.486L20.5 13"></path>
            </svg>
          </button>
          <button type="button" class="tw-inline-flex tw-items-center tw-justify-center tw-rounded-full tw-h-10 tw-w-10 tw-transition tw-duration-500 tw-ease-in-out tw-text-gray-500 hover:tw-bg-gray-300 focus:tw-outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="tw-h-6 tw-w-6 tw-text-gray-600">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.172 7l-6.586 6.586a2 2 0 102.828 2.828l6.414-6.586a4 4 0 00-5.656-5.656l-6.415 6.585a6 6 0 108.486 8.486L20.5 13"></path>
            </svg>
          </button>
          <button type="button" class="tw-inline-flex tw-items-center tw-justify-center tw-rounded-full tw-h-12 tw-w-12 tw-transition tw-duration-500 tw-ease-in-out tw-text-white tw-bg-blue-500 hover:tw-bg-blue-400 focus:tw-outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="tw-h-6 tw-w-6 tw-transform tw-rotate-90">
              <path d="M10.894 2.553a1 1 0 00-1.788 0l-7 14a1 1 0 001.169 1.409l5-1.429A1 1 0 009 15.571V11a1 1 0 112 0v4.571a1 1 0 00.725.962l5 1.428a1 1 0 001.17-1.408l-7-14z"></path>
            </svg>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {}
};
</script>
<style>

</style>
