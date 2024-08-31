<script lang="ts" setup>
definePageMeta({
  middleware: 'verified',
})

const title = 'Dashboard'

useSeoMeta({
  title,
})
</script>

<template>
  <UContainer>
    {{title}}
  </UContainer>
</template>
