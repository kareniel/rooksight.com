<template>  
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<script setup lang="ts">
const title = ref('Rooksight');

useHead({
  title: title,
  meta: [{
    name: 'viewport',
    content: "width=device-width, initial-scale=1.0",
  }, {
    name: 'description',
    content: "To reduce the cybersecurity burden of entrepreneurs.",
  }, {
    name: 'keywords',
    content: "Cybersecurity, startup, SaaS, B2B, compliance, SOC 2, ISO 27001",
  }, {
    name: 'author',
    content: "Rooksight",
  }],
  script: [{
    src: "https://www.googletagmanager.com/gtag/js?id=GTM-5RG8GNXB",
    async: true
  },{
    src: "https://f.convertkit.com/ckjs/ck.5.js",
    async: true
  }],
  link: [{
    rel: "stylesheet",
    href: "https://unpkg.com/tachyons@4.12.0/css/tachyons.min.css"
  }, {
    rel: "stylesheet",
    href: "/css/style.css"
  }]
});

</script>
