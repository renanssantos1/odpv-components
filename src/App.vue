<template>
  <div id="app" class="container">
    <header>
      <ul class="row">
        <li class="col-3 col-md-3 col-lg-4 col-xl-2">
          <router-link to="/">Home</router-link>
        </li>
        <li class="col-3 col-md-3 col-lg-6 col-xl-1">
          <router-link to="/button">button</router-link>
        </li>
        <li class="col-2 col-md-3 col-lg-1 col-xl-6">
          <router-link to="/switch">switch</router-link>
        </li>
        <li class="col-4 col-md-3 col-lg-1 col-xl-3">
          <router-link to="/form">form</router-link>
        </li>
      </ul>
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
