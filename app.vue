<template>
  <div class="container">
    <navbar />
    <NuxtPage />
  </div>
</template>

<script setup>
const title = ref('Hello World')

</script>

<script>
export default {
  head() {
    return {
      link: [
        {
          rel: 'stylesheet',
          href: 'https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css'
        }
      ],
      script: [
        {
          src: "https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js",
          type: 'text/javascript'
        },
      ]
    }
  }
}
</script>