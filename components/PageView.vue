<script setup lang="ts">
const { data } = await useFetch('/api/pageview')

const time = useTimeAgo(computed(() => data.value.startAt))
</script>

<template>
  <div text-gray:80>
    An opionated view on the future of software engineering.
  </div>
</template>
