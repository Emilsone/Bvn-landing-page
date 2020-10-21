<template>
  <div>
    <hero />
    <call-to-action />
  </div>
</template>

<script>
import Hero from '@/components/Hero'

export default {
  name: 'LandingPage',
  components: {
    hero: Hero
  }
}
</script>
