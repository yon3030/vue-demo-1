<template>
  <UpperBanner />
  <TheFeatures />
</template>

<script>
import UpperBanner from "@/components/Home/UpperBanner.vue";
import TheFeatures from "@/components/Home/TheFeatures.vue";

export default {
  name: "HomeView",
  components: {
    UpperBanner,
    TheFeatures,
  },
};
</script>
