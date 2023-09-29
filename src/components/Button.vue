<script setup>
defineProps({
  text: {
    type: String,
    default: 'Button'
  },
  size: {
    type: String,
    options: ['small', 'sm', 'medium', 'md', 'large', 'lg'],
    default: 'medium'
  }
})
</script>

<template>
  <button :class="size">
    {{ text }}
  </button>
</template>
