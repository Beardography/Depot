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
  },
  type: {
    type: String,
    options: ['primary', 'secondary', 'danger', 'danger-secondary']
  }
})
</script>

<template>
  <button :class="[size, type]">
    {{ text }}
  </button>
</template>
