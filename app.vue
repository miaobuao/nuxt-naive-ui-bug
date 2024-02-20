<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<script setup lang="ts">
import {useNotification} from "naive-ui"

const notify = useNotification()

notify.create({
  type: "info",
  content: "baga"
})
</script>