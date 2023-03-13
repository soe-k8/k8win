<template>
  <section>
    <h1 class="text-white align-center"> Claim your Bonus </h1>
    <div class="flex flex-row items-center justify-center my-12">
      <h2 class="text-white mr-9 text-base">K8.io</h2>
      <span class="bg-dark-100 p-13px rounded-5px w-52 align-center">
        <a href="https://k8.io/promotions" class="text-swam-white-600 text-13px decoration-none" target="_blank">https://k8.io/promotions</a>
      </span>
    </div>
  </section>
  <section>
    <p class="text-white text-base align-center my-9">If you are looking for the bonus link for an official Stake.com mirror site, then use one of the following:</p>
    <div class="mt-4">
      <div class="flex flex-row items-center justify-center mb-4" v-for="(val,key) in urlList">
        <h2 class="text-white mr-9 text-base">{{val.name}}</h2>
        <span class="bg-dark-100 p-13px rounded-5px inline-block w-52 align-center">
          <a href="https://k8.io/promotions" class="text-swam-white-600 text-13px decoration-none">{{val.url}}</a>
        </span>
      </div>
    </div>
  </section>
  <section style="max-width: 600px;" class="bg-dark-100 py-1 px-8 text-swam-white-600 mt-6 rounded-5px">
    <div>
      <h1 class="text-xl"> What is a mirror site?</h1>
      <p class="text-base">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aperiam blanditiis commodi dolorum exercitationem ipsam maxime nostrum obcaecati placeat praesentium quo repudiandae saepe tempore, temporibus veniam vero voluptatem voluptatum. Consequuntur, similique.
      </p>
    </div>
  </section>
</template>

<script setup lang="ts">
import {ref} from "vue";
useHead({
  titleTemplate: "Top of world Crypto Gambling - K8",
  meta: [
    {
      property:"og:image:width",
      content: "1200"
    },
    {
      property:"og:image:height",
      content: "630"
    },
    {
      property:"og:site_name",
      content: "K8 Casino"
    },
    {
      property:"og:title",
      content: "Top of world Crypto Gambling - K8"
    },
    {
      property:"og:description",
      content: "More than 3000 games available at K8. Play games ranging from Slots, Roulette, Game Shows and receive promotion more than 30%"
    },
    {
      property:"og:type",
      content: "blog"
    },
    {
      property:"og:url",
      content: "https://k8win.io"
    },
    {
      property:"og:image",
      content: "/img/logo.png"
    },
    {
      name:"description",
      content: "More than 3000 games available at K8. Play games ranging from Slots, Roulette, Game Shows and receive promotion more than 30%"
    },
    {
      name:"twitter:title",
      content: "Top of world Crypto Gambling - K8"
    },
    {
      name:"twitter:description",
      content: "More than 3000 games available at K8. Play games ranging from Slots, Roulette, Game Shows and receive promotion more than 30%"
    },
    {
      name:"twitter:image",
      content: "/img/logo.png"
    },
    {
      name:"twitter:card",
      content: "summary_large_image"
    },
    {
      name:"twitter:site",
      content: "@_k8gaming"
    },
  ]
});

const urlList = [
  {
    name: "K8",
    url: "https://k8.io"
  },
  {
    name: "K8 Casino",
    url: "https://k8casino.io"
  },
  {
    name: "K8 Bit",
    url: "https://k8bit.io"
  },
  {
    name: "K8 Casino1",
    url: "https://k8casino1.com"
  },
  {
    name: "K8 Casino2",
    url: "https://k8casino2.com"
  },
]

</script>

<style scoped>

</style>