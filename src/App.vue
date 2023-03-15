<template>
  <Suspense>
    <template #default>
      <ProfileCard></ProfileCard>
    </template>
    <template #fallback>
      <ProfileCardSkeleton></ProfileCardSkeleton>
    </template>
  </Suspense>
</template>
<script setup>

import ProfileCard from "./components/ProfileCard.vue";
import ProfileCardSkeleton from "./components/ProfileCardSkeleton.vue";
</script>
<style scoped>


</style>
