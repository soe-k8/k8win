<template>
  <section>
    <h1 class="text-white align-center"> K8 Official Mirror List </h1>
  </section>
  <section>
    <p class="text-white text-base align-center my-9 text-xl">Can't access k8.io? Try one of these mirror sites below:</p>
    <div class="mt-4">
      <div class="flex flex-row items-center justify-center mb-3" v-for="(val,key) in urlList">
        <h2 class="text-white mr-9 w-51 text-xl" v-if="val.type == 'title'">{{val.name}}</h2>
        <a :onclick="'window.open(\''+val.url+'\')'" href="javascript:void(0);" class="text-white mr-9 w-51" v-else>
          <h2 class="text-base">{{val.name}}</h2>
        </a>
<!--        <span class="bg-dark-100 p-13px rounded-5px inline-block w-52 align-center">-->
<!--          <a href="https://k8.io/promotions" class="text-swam-white-600 text-13px decoration-none">{{val.url}}</a>-->
<!--        </span>-->
        <span class="inline-block lowercase decoration-none" :class="val.type == 'title'? 'text-white text-xl' : 'text-green-100 text-base '"> {{val.status}}</span>
      </div>
    </div>
  </section>
  <section style="max-width: 600px;" class="bg-dark-100 py-1 px-8 text-swam-white-600 mt-6 rounded-5px">
    <div>
      <h1 class="text-xl"> What is a mirror site?</h1>
      <p class="text-base">
        A mirror site is a duplicate of an existing website, created to minimize network congestion or enhance the accessibility of the primary website. The mirrors mentioned are exact replicas of k8.io and are accessible through various URLs to aid users experiencing connectivity problems with K8.
      </p>
    </div>
  </section>
</template>

<script setup lang="ts">
import {ref} from "vue";
useHead({
  titleTemplate: "k8.io | Official Mirror List",
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
      content: "k8.io | Official Mirror List"
    },
    {
      property:"og:description",
      content: "Sources for K8.io and its authorized repositories."
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
      content: "/img/shared_logo.png"
    },
    {
      name:"description",
      content: "Sources for K8.io and its authorized repositories."
    },
    {
      name:"twitter:title",
      content: "k8.io | Official Mirror List"
    },
    {
      name:"twitter:description",
      content: "Sources for K8.io and its authorized repositories."
    },
    {
      name:"twitter:image",
      content: "/img/shared_logo.png"
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
    name: "Sites",
    url: "https://k8.io",
    status: 'Status',
    type:'title',
  },
  {
    name: "K8.io",
    url: "https://k8.io",
    status: "online",
    type:'content',
  },
  {
    name: "K8casino.io",
    url: "https://k8casino.io",
    status: "online",
    type:'content',
  },
  {
    name: "K8bit.io",
    url: "https://k8bit.io",
    status: "online",
    type:'content',
  },
  {
    name: "K8casino1.com",
    url: "https://k8casino1.com",
    status: "online",
    type:'content',
  },
  {
    name: "K8casino2.com",
    url: "https://k8casino2.com",
    status: "online",
    type:'content',
  },
]

</script>

<style scoped>

</style>