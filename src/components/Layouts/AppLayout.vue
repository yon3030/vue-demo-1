<template>
  <v-layout>
    <AppNavigations />
    <Header />
    <v-main>
      <slot></slot>
    </v-main>
    <AppFooter />
  </v-layout>
</template>

<script>
import Header from "@/components/Layouts/partial/AppHeader.vue";
import AppFooter from "@/components/Layouts/partial/AppFooter.vue";
import AppNavigations from "@/components/Layouts/partial/AppNavigations.vue";
export default {
  name: "AppLayout",
  data() {
    return {};
  },
  components: {
    Header,
    AppNavigations,
    AppFooter,
  },
};
</script>
