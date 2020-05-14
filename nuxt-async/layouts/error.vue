<template>
  <div class="container">
      This is ErroPage
      {{ error.message }}
  </div>
</template>

<script>
export default {
    props: ['error']
}
</script>