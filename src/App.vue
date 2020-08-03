<template>
  <div id="app" class="container">
    <header>
      <ul>
        <li>
          <router-link to="/">Home</router-link>
        </li>
        <li>
          <router-link to="/button">button</router-link>
        </li>
        <li>
          <router-link to="/switch">switch</router-link>
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
