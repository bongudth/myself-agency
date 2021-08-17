<template>
  <div id="app">
    <ContactUs />
    <Design />
  </div>
</template>

<script>
import ContactUs from "./components/ContactUs.vue";
import Design from "./components/Design.vue";

export default {
  name: "App",
  components: {
    ContactUs,
    Design,
  },
};
</script>

<style lang="scss">
#app {
  font-family: "Open Sans", sans-serif;
  background-color: #f2f2f2;
  // font-family: "Montserrat", sans-serif;
  // font-family: "Oswald", sans-serif;
  // font-family: "Roboto", sans-serif;
}
</style>
