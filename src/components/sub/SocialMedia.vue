<template>
  <section>
    <img src="@/assets/icons/fb-logo.svg" alt="facebook logo">
    <img src="@/assets/icons/twitter-logo.svg" alt="twitter logo">
    <img src="@/assets/icons/inst-logo.svg" alt="instagram logo">
    <img src="@/assets/icons/tel-logo.svg" alt="telegram logo">
  </section>
</template>

<script>
export default {
    name: "SocialMedia"
}
</script>

<style scoped>
section {
  display: flex;
    justify-content: space-evenly;
  justify-self: center;
  margin-bottom: 48px;
  width: 240px;
}
</style>
