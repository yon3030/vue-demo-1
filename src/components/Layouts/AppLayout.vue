<template>
  <v-layout>
    <AppNavigations />
    <AppNavBar />
    <v-main>
      <slot></slot>
    </v-main>
    <AppFooter />
  </v-layout>
</template>

<script>
import AppNavBar from "./AppNavBAr.vue";
import AppFooter from "./AppFooter.vue";
import AppNavigations from "./AppNavigations.vue";
export default {
  name: "AppLayout",
  data() {
    return {
      drawer: true,
    };
  },
  components: {
    AppNavBar,
    AppNavigations,
    AppFooter,
  },
};
</script>
