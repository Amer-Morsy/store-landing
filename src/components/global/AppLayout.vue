<template>
  <div class="layout">
    <v-layout class="position-relative">
      <CartDrawer />
      <AppNav />
      <v-main style="padding-top: 150px">
        <slot> </slot>
      </v-main>
      <AppFooter />
    </v-layout>
  </div>
</template>

<script>
import AppNav from "@/components/global/AppNav.vue";
import CartDrawer from "@/components/global/CartDrawer.vue";
import AppFooter from "@/components/global/AppFooter.vue";

export default {
  name: "AppLayout",
  components: {
    AppNav,
    CartDrawer,
    AppFooter,
  },
  data() {
    return {};
  },
};
</script>
