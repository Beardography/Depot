<script setup>
defineProps({
  text: {
    type: String,
    default: 'Link'
  },
  href: {
    type: String,
    default: '#'
  },
  target: {
    type: String,
    default: '_self'
  },
  rel: {
    type: String,
    default: ''
  }
})
</script>

<template>
  <a :href="href" :target="target">{{ text }}</a>
</template>
