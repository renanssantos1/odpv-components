<template>
  <div id="app">
    <button class="odpv btn">
      <span>button</span>
    </button>

    <button class="odpv btn btn--bordered">
      <span>button</span>
    </button>

    <button class="odpv btn btn--loading">
      <span>button</span>
    </button>

    <button class="odpv btn btn--facebook">facebook</button>

    <button class="odpv btn btn--orange btn--bordered" type="button">
      Orange
    </button>

    <button class="odpv btn btn--orange btn--link" type="button">
      Orange
    </button>

    <a href="#" :title="`${titulo}  renan`">{{ titulo }}</a>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      titulo: "Meu titulo maroto",
    };
  },
};
</script>

<style lang="scss">
@import "./assets/scss/_app.scss";
</style>
