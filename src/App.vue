<script setup>
import GettingStarted from "./components/GettingStarted.vue";
import MultiStepForm from "./components/MultiStepForm.vue";
</script>

<template>
  <GettingStarted>
    <template #intro-text>
      <div>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero nostrum
          animi distinctio aperiam, sunt, exercitationem atque sed dignissimos
          earum dolore est, voluptatem similique. Eveniet odio dolorum
          consequuntur voluptate animi inventore!
        </p>
      </div>
    </template>
  </GettingStarted>
  <MultiStepForm />
</template>

<style scoped></style>
