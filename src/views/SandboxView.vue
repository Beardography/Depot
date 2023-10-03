<script setup>
import Switch from '../components/Switch.vue'
</script>

<template>
  <Switch label="With Label" :showLabel="true" for="tester" />
  <br /><br />
  <Switch label="With Label" :showLabel="true" size="large" />
</template>
