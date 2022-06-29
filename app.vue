<template>
  <div>
    <navbar />
    <NuxtPage />
  </div>
</template>

<script>
export default {
  head() {
    return {
      link: [
        {
          rel: 'stylesheet',
          href: '	https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css'
        }
      ],
      script: [
        {
          src: "	https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js",
          type: 'text/javascript'
        },
      ]
    }
  }
}
</script>