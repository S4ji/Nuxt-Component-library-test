<script setup lang="ts">
const isOpen = ref(false)
</script>

<template>
  <div>
    <UButton label="Open" @click="isOpen = true" />

    <USlideover v-model="isOpen">
      <div class="flex-1">
      </div>
    </USlideover>
  </div>
</template>

<style>

</style>