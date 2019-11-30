<template>
  <div class="layout">
    <Header />
    <slot/>
    <Footer />
  </div>
</template>

<script>
import Header from '~/components/Header'
import Footer from '~/components/Footer'

export default {
  components: {
    Header,
    Footer
  }  
}
</script>

<style>
h2 {
  @apply text-2xl mb-8;
}

h3 {
  @apply text-2xl font-bold mb-4;
}

p {
  @apply text-xl mb-8;
}

blockquote {
  @apply border-l-4 border-purple-400 p-4 pl-6 text-xl mb-4 bg-gray-200;
}

details {
  @apply text-xl mb-4;
}

summary {
  @apply font-bold;
}

a {
  @apply underline text-purple-600;
}
</style>