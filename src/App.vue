<script>
import helloVue from "./components/AppTitle.vue";

import helloHero from "./components/AppHero.vue";

export default {
  components: {
    helloVue,
    helloHero
  }
}
</script>

<template>
  <helloVue />
  <helloHero />
</template>