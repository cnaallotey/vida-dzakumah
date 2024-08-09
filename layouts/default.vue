<script setup>

const meta = {
    title: 'Vida Dzakumah',
    description: 'In loving memory of the Late Vida Mawusi Dzakumah - 88 Years'
}

 useSeoMeta({
    title: meta.title,
    ogTitle: meta.title,
    description: meta.description,
    ogDescription: meta.description,
    ogImage: '/images/meta.png',
    twitterCard: 'summary_large_image'
  })

useHead({
  link: [
    { rel: 'icon', type: 'image/x-icon', href: '/images/oma.ico' }
  ]
})
</script>

<template>
    <div class="w-full">
        <slot />
    </div>
</template>