<script setup>
const props = defineProps(["heading"]);
</script>

<template>
  <h2>{{ heading }}</h2>
  <div class="step-form">
    <slot name="step-form"></slot>
  </div>
</template>

<style scoped>
.step-form {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
