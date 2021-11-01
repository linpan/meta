<template>
  <div class="tw-h-screen tw-flex tw-flex-col tw-mx-auto tw-justify-between">
    <Connect></Connect>
    <div class="message-box tw-flex-1 tw-overflow-y-auto">
      <div class="chat-left tw-p-2 tw-m-1">
        <div class="tw-flex tw-items-end tw-w-7/8">
          <div class="tw-flex tw-flex-col tw-space-y-2 tw-text-sm tw-max-w-xs tw-mx-2 tw-order-2 tw-items-start">
            <div><span
              class="tw-px-2 tw-py-2  tw-rounded-lg tw-inline-block tw-rounded-bl-none tw-bg-white tw-font-normal">今天的天气如何？</span>
            </div>
          </div>
          <img
            src="https://images.unsplash.com/photo-1549078642-b2ba4bda0cdb?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=3&amp;w=144&amp;h=144"
            alt="My profile" class="tw-w-10 tw-h-10 tw-rounded-full tw-order-1">
        </div>
      </div>
      <div class="chat-right tw-m-2">
        <div class="tw-flex tw-items-end tw-justify-end tw-w-7/8">
          <div class="tw-w-1/5 v-space"></div>
          <div class="tw-flex tw-flex-col tw-space-y-2 tw-text-xs tw-max-w-xs tw-mx-2 tw-order-1 tw-items-end">
            <div><span
              class="tw-px-2 tw-py-2 tw-rounded-lg tw-inline-block tw-rounded-br-none tw-bg-regal-blue tw-text-black tw-text-sm tw-font-normal">我无法理解你的问题</span>
            </div>
          </div>
          <img
            src="https://images.unsplash.com/photo-1590031905470-a1a1feacbb0b?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=3&amp;w=144&amp;h=144"
            alt="My profile" class="tw-w-10 tw-h-10 tw-rounded-full tw-order-2">
        </div>
      </div>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import  Connect from "../components/Connect.vue";
import Footer from "../components/Footer";

export default {
  name: "Home",
  components: { Footer, Connect }
};
</script>
<style>

</style>
