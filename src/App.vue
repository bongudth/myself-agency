<template>
  <div id="app">
    <SectionOne />
    <SectionTwo />
  </div>
</template>

<script>
import SectionOne from "./components/SectionOne.vue";
import SectionTwo from "./components/SectionTwo.vue";

export default {
  name: "App",
  components: {
    SectionOne,
    SectionTwo,
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
