<script setup>
import Link from '../components/Link.vue'
import Button from '../components/Button.vue'
import Tag from '../components/Tag.vue'
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

  <br />
  <br />
  <br />
  <h3>Tags</h3>
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
