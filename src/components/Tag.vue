<script setup>
defineProps({
  text: {
    type: String,
    default: 'Tag'
  },
  size: {
    type: String,
    options: ['medium', 'md', 'large', 'lg'],
    default: 'medium'
  },
  status: {
    type: String,
    options: ['success', 'error', 'warning', 'waiting', 'processing', 'info']
  },
  color: {
    type: String,
    options: ['orange', 'purple', 'blue', 'green', 'yellow', 'red', 'default']
  }
})
</script>

<template>
  <div class="tag" :class="[size, status, color]">
    {{ text }}
  </div>
</template>
