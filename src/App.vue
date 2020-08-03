<template>
  <div id="app" class="container">
    <header>
      <router-link to="/">Home</router-link>

      <router-link to="/button">Button</router-link>
    </header>

    <main>
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style lang="scss">
@import "./assets/scss/_app.scss";
</style>
