<template>
  <div class="home">
    <UpperBanner />
    <TheFeatures />
  </div>
</template>

<script>
import TheFeatures from "@/components/home_page/TheFeatures.vue";
import UpperBanner from "@/components/home_page/UpperBanner.vue";

export default {
  name: "HomeView",
  components: { UpperBanner, TheFeatures },
};
</script>
