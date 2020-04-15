<template>
  <layout>
    <Hero />
    <Services />
    <About />
  </layout>
</template>

<script>
import Hero from "../components/Hero";
import About from "../components/About";
import Services from "../components/Services";
export default {
  components: {
    Hero,
    About,
    Services
  }
};
</script>

<style></style>
