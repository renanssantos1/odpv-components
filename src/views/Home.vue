<template>
  <div class="home">
    <div class="row">
      <div
        class="col-xs-6
                col-sm-8
                col-md-6
                col-lg-4"
      >
        <div class="box">Responsive</div>
      </div>

      <div
        class="col-xs-6
                col-sm-8
                col-md-6
                col-lg-4"
      >
        <div class="box">Responsive</div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>

<style lang="scss">
.box {
  background: blue;
  color: #fff;
}
</style>
