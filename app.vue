<script setup>
useHead({
  bodyAttrs: {
    class: 'bg-black'
  },
  meta: [
    { name: 'theme-color', content: '#1d2030' }
  ],
  link: [
    { rel: 'icon', type: 'image/png', href: '/favicon-96x96.png', sizes: '96x96' },
    { rel: 'icon', type: 'image/svg+xml', href: '/favicon.svg' },
    { rel: 'shortcut icon',href: '/favicon.ico' },
    { rel: 'apple-touch-icon', sizes: '180x180', href: '/apple-touch-icon.png' },
    { rel: 'manifest', href: '/site.webmanifest' },
  ]
})

const title = 'disEdit - Web development for organizations'
const description = 'We develop custom-made digital tools and websites for organizations and non-profits'

useSeoMeta({
  title,
  ogTitle: title,
  description,
  ogDescription: description,
  ogImage: 'https://disedit.com/ogimage.png',
  twitterCard: 'summary_large_image',
})
</script>

<template>
  <div class="flex flex-col h-[100dvh] text-white items-start text-md">
    <Logo class="w-full md:w-auto md:h-[10rem]" />

    <div class="p-site mt-auto">
      <p class="text-xl text-balance leading-[1.1]">
        We develop <span class="text-blue">custom-made digital tools
          <br class="hidden md:block">
          and websites</span> for organizations and non-profits.
      </p>

      <p class="mt-6 font-light">
        Get in touch with us at
        <a href="mailto:info@disedit.com" class="text-orange hover:underline">
          info@disedit.com
        </a>
      </p>
    </div>
  </div>
</template>
