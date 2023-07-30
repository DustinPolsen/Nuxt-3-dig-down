<template>
  <div>
    Directly Grab {{ $route.params.user_id }}
    Normally Grab {{user_id}}
  </div>
</template>

<script setup lang="ts">
const { user_id } = useRoute().params;
</script>

<style scoped>
</style>