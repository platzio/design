<template>
  <img
    src="../assets/Logo.svg"
    :style="{
      width: props.size,
      height: props.size,
    }"
  />
</template>

<script setup lang="ts">
const props = withDefaults(defineProps<{ size: string }>(), { size: "2rem" });
</script>
