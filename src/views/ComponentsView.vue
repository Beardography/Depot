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
  <Button size="lg" text="Add to cart" type="primary" />
  <Button size="md" text="Add to cart" type="primary" />
  <Button size="sm" text="Add to cart" type="primary" />
  <br /><br />
  <Button size="lg" text="Add to cart" type="secondary" />
  <Button size="md" text="Add to cart" type="secondary" />
  <Button size="sm" text="Add to cart" type="secondary" />
  <br /><br />
  <Button size="lg" text="Add to cart" type="danger" />
  <Button size="md" text="Add to cart" type="danger" />
  <Button size="sm" text="Add to cart" type="danger" />
  <br /><br />
  <Button size="lg" text="Add to cart" type="danger-secondary" />
  <Button size="md" text="Add to cart" type="danger-secondary" />
  <Button size="sm" text="Add to cart" type="danger-secondary" />
  <br /><br />
  <Button size="lg" text="Add to cart" disabled />
</template>
