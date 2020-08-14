<template>
  <div id="app">
    <the-header></the-header>

    <div class="container content">
      <main>
        <router-view></router-view>
      </main>
    </div>

    <the-footer></the-footer>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {
    TheHeader: () => import("@/components/TheHeader.vue"),
    TheFooter: () => import("@/components/TheFooter.vue"),
  },
};
</script>

<style lang="scss">
@import "./assets/scss/_app.scss";
</style>
