/* eslint-disable prettier/prettier */
<template>
  <div>
    <the-header />
    <nuxt />
    <the-footer />
  </div>
</template>

<script>
import TheHeader from '~/components/TheHeader'
import TheFooter from '~/components/TheFooter'

export default {
  middleware: [],
  components: { TheHeader, TheFooter },
  created() {},
  mounted() {}
}
</script>

<style></style>
