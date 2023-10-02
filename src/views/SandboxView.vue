<script setup>
import Tag from '../components/Tag.vue'
</script>

<template>
  <Tag size="lg" text="this is a tag and all this other stuff" />
  <Tag size="md" />

  <br /><br />

  <!-- Statuses -->
  <Tag status="success" />
  <Tag status="error" />
  <Tag status="warning" />
  <Tag status="waiting" />
  <Tag status="processing" />
  <Tag status="info" />

  <br /><br />

  <!-- Colors -->
  <Tag color="orange" />
  <Tag color="purple" />
  <Tag color="blue" />
  <Tag color="green" />
  <Tag color="yellow" />
  <Tag color="red" />
  <Tag color="default" />
</template>
