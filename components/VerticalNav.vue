<script setup lang="ts">
const route = useRoute()

const links = [{
  label: 'Profile',
  avatar: {
    src: 'https://avatars.githubusercontent.com/u/739984?v=4'
  },
  badge: 100
}, {
  label: 'Installation',
  icon: 'i-heroicons-home',
  to: '/getting-started/installation'
},]
</script>

<template>
  <UVerticalNavigation :links="links" />
</template>

<style>

</style>