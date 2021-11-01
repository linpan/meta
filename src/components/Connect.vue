<template>
  <div
    class="header  tw-w-full tw-h-16 tw-flex tw-justify-between tw-px-2 tw-items-center tw-px-4 tw-border-b tw-border-gray-300">
    <div class="return-icon">
      <svg xmlns="http://www.w3.org/2000/svg" class="tw-h-6 tw-w-6 tw-text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M15 19l-7-7 7-7" />
      </svg>
    </div>
    <div class="tw-flex-1 tw-text-center tw-font-medium ">我和小呆的日常👽</div>
    <div class="more-dots">
      <svg xmlns="http://www.w3.org/2000/svg" class="tw-h-6 tw-w-6 tw-text-gray-600" viewBox="0 0 20 20" fill="currentColor">
        <path d="M6 10a2 2 0 11-4 0 2 2 0 014 0zM12 10a2 2 0 11-4 0 2 2 0 014 0zM16 12a2 2 0 100-4 2 2 0 000 4z" />
      </svg>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>

</style>