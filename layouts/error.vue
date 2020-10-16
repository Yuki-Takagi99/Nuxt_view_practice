<template>
  <div>
    <h1 v-if="error.statusCode === 404">404Error!</h1>
  </div>
</template>

<script>
export default {
  name: "error",
  props: ['error']
}
</script>

<style scoped>

</style>
