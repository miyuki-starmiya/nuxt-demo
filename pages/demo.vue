<template>
  <main>
    <h1>This is demo page !</h1>

    <nuxt-link to="/">jump index</nuxt-link>

  </main>
</template>

<script>
export default {
  mounted() {
    console.log(process.env.STRIPE_PK);
  }
}
</script>

