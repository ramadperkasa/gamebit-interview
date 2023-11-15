<template>
  <div class="w-full">
    <SectionTitle />

    <div class="w-full bg-gray-200 p-2 my-5"></div>

    <SectionDescription />
  </div>
</template>

<script setup lang="ts">
import { onMounted } from "vue";
import { initFlowbite } from "flowbite";

onMounted(() => {
  initFlowbite();
});
</script>
