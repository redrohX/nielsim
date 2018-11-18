<template>
  <div class="container">
    <h1 v-if="error.statusCode === 404">Page not found</h1>
    <h1 v-else>An error occurred: 404</h1>
  </div>
</template>

<script>
export default {
  props: {
    error: {
      type: String,
      default: ''
    }
  },
  layout: 'blog' // you can set a custom layout for the error page
}
</script>
