<script lang="ts" setup>
definePageMeta({
  middleware: 'auth',
})

const title = 'Profile'
const description = 'Manage your profile settings.'

useSeoMeta({
  title,
  description,
})
</script>

<template>
  <UContainer>
      <ProfileSectionInformation />

        <ProfileSectionProviders />

        <UDivider />

        <ProfileSectionDeleteAccount />
  </UContainer>
</template>
