<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  data() {
    return {

    };
  },

  components: { AppTitle, AppHero },
};
</script>

<template>
  <header>
    <app-title />
    <app-hero />
  </header>
</template>

<style></style>