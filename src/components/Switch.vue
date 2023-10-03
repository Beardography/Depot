<script setup>
defineProps({
  label: {
    type: String,
    default: 'Switch'
  },
  showLabel: {
    type: Boolean,
    default: true,
    required: true
  },
  size: {
    type: String,
    options: ['medium', 'md', 'large', 'lg'],
    default: 'medium'
  }
})
</script>

<template>
  <div class="toggle" :class="[size]">
    <label v-show="showLabel" class="label">{{ label }}</label>
    <label class="switch">
      <input type="checkbox" />
      <div class="slider"></div>
    </label>
  </div>
</template>
