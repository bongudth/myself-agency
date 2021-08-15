<template>
  <div id="app">
    <ContactUs />
  </div>
</template>

<script>
import ContactUs from "./components/ContactUs.vue";

export default {
  name: "App",
  components: {
    ContactUs,
  },
};
</script>

<style lang="scss">
#app {
  font-family: "Open Sans", sans-serif;
  // font-family: 'Montserrat', sans-serif;
  // font-family: 'Oswald', sans-serif;
  // font-family: 'Roboto', sans-serif;
}
</style>
