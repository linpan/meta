<template>
  <div class="footer-input tw-w-full tw-border-t tw-border-gray-300">
    <div class="tw-flex tw-p-1">
      <div class="speaker">
        <button type="button"
                class="tw-inline-flex tw-items-center tw-justify-center tw-rounded-full tw-h-12 tw-w-12 focus:tw-outline-none">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"
               class="tw-h-6 tw-w-6 tw-text-gray-500">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="M19 11a7 7 0 01-7 7m0 0a7 7 0 01-7-7m7 7v4m0 0H8m4 0h4m-4-8a3 3 0 01-3-3V5a3 3 0 116 0v6a3 3 0 01-3 3z"></path>
          </svg>
        </button>
      </div>
      <input type="text" placeholder="Tying a message..."
             class="focus:tw-outline-none tw-flex-grow tw-rounded tw-text-base tw-px-1">
      <div class="tw-items-center">
        <button type="button"
                class="tw-inline-flex tw-items-center tw-justify-center tw-rounded-full tw-h-12 tw-w-12 tw-p-1 tw-transition tw-duration-500 tw-ease-in-out tw-text-gray-500  focus:tw-outline-none">
          <svg xmlns="http://www.w3.org/2000/svg" class="tw-h-6 tw-w-6 tw-text-gray-500" viewBox="0 0 20 20"
               fill="currentColor">
            <path fillRule="evenodd"
                  d="M4 2a1 1 0 011 1v2.101a7.002 7.002 0 0111.601 2.566 1 1 0 11-1.885.666A5.002 5.002 0 005.999 7H9a1 1 0 010 2H4a1 1 0 01-1-1V3a1 1 0 011-1zm.008 9.057a1 1 0 011.276.61A5.002 5.002 0 0014.001 13H11a1 1 0 110-2h5a1 1 0 011 1v5a1 1 0 11-2 0v-2.101a7.002 7.002 0 01-11.601-2.566 1 1 0 01.61-1.276z"
                  clipRule="evenodd" />
          </svg>
        </button>
        <button type="button"
                @click="showme"
                class="tw-inline-flex flex-no-shrink  border-transparent  tw-cursor-auto tw-items-center tw-justify-center tw-rounded-full tw-h-12 tw-w-12 tw-text-white  tw-text-gray-500 focus:tw-outline-none">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor"
               class="tw-h-6 tw-w-6 tw-transform tw-rotate-45 tw-text-gray-500">
            <path
              d="M10.894 2.553a1 1 0 00-1.788 0l-7 14a1 1 0 001.169 1.409l5-1.429A1 1 0 009 15.571V11a1 1 0 112 0v4.571a1 1 0 00.725.962l5 1.428a1 1 0 001.17-1.408l-7-14z"></path>
          </svg>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  methods: {
    showme() {
      console.log("click to show...");

    }
  }
};
</script>

<style scoped>

</style>