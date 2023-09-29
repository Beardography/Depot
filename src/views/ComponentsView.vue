<script setup>
import Link from '../components/Link.vue'
import Button from '../components/Button.vue'
</script>

<template>
  <h1>Components</h1>
  <h3>Link Component</h3>
  <Link target="_blank" href="https://www.google.com" text="this is a link" />

  <br /><br /><br />

  <h3>Buttons</h3>
  <Button size="lg" text="Button" />
  <br />
  <br />
  <Button size="md" text="Button" />
  <br />
  <br />
  <Button size="sm" text="Button" />
</template>
