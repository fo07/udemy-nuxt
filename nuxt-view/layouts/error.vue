<template>
  <div>
    <h1 v-if="error.statusCode === 404">Error{{ error.statusCode }}</h1>
    <!-- <nuxt /> -->
  </div>
</template>

<script>
export default {
    props: ['error']
}
</script>
