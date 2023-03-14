<template>
  <footer class="mt-6">
    <div class="flex">
<!--      <a href="https://www.youtube.com/channel/UCuNeezIgedTaCbYWQ4ryX1g" target="_blank">-->
<!--          <img-->
<!--            class="mr-2.5"-->
<!--            src="/img/logo-youtube@1x.svg"-->
<!--            alt="K8 Casino Youtube Channel"-->
<!--          >-->
<!--      </a>-->
      <a :onclick="'window.open(\'https://www.instagram.com/k8.io_official\', \'_blank\')'" href="javascript:void(0);">
          <img
            class="mr-2.5"
            src="/img/logo-ig@1x.svg"
            alt="K8 Casino Instagram Channel"
            loading="lazy"
          >
      </a>
      <a :onclick="'window.open(\'https://www.facebook.com/k8.io.official\', \'_blank\')'" href="javascript:void(0);">
          <img
            class="mr-2.5"
            src="/img/logo-fb.svg"
            alt="K8 Casino Facebook Channel"
            loading="lazy"
          >
      </a>
      <a :onclick="'window.open(\'https://twitter.com/k8official_en\', \'_blank\')'" href="javascript:void(0);">
          <img
            class="mr-2.5"
            src="/img/logo-twitter@1x.svg"
            alt="K8 Casino Twitter Channel"
            loading="lazy"
          >
      </a>
      <a :onclick="'window.open(\'https://www.twitch.tv/k8_official\', \'_blank\')'" href="javascript:void(0);">
          <img
            class="mr-2.5"
            src="/img/logo-twitch@1x.svg"
            alt="K8 Casino Twitch Channel"
            loading="lazy"
          >
      </a>
      <a :onclick="'window.open(\'https://www.tiktok.com/@k8.io_official\', \'_blank\')'" href="javascript:void(0);">
          <img
            src="/img/logo-Tiktok@1x.svg"
            alt="K8 Casino Tiktok Channel"
            loading="lazy"
          >
      </a>
    </div>
  </footer>
</template>

<script lang="ts">
export default {
  name: "AppFooter"
}
</script>

<style scoped>

</style>