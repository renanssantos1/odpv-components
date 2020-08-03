<template>
  <section>
    <label class="odpv switch--container" for="switch">
      <input id="switch" class="odpv switch" type="checkbox" />
      <span>aceito os termos</span>
    </label>

    <label class="odpv switch--container" for="switch-facebook">
      <input id="switch-facebook" class="odpv switch switch--facebook" type="checkbox" />
      <span>aceito os termos</span>
    </label>

    <label class="odpv switch--container" for="switch-primary">
      <input id="switch-primary" class="odpv switch switch--primary" type="checkbox" />
      <span>aceito os termos</span>
    </label>

    <label class="odpv switch--container" for="switch-secondary">
      <input id="switch-secondary" class="odpv switch switch--secondary" type="checkbox" />
      <span>aceito os termos</span>
    </label>

    <label class="odpv switch--container" for="switch-black">
      <input id="switch-black" class="odpv switch switch--black" type="checkbox" />
      <span>aceito os termos</span>
    </label>

    <input id="switch-orange" class="odpv switch switch--orange" type="checkbox" />

    <input disabled id="switch-orange" class="odpv switch switch--orange" type="checkbox" />

    <input
      v-model="check"
      disabled
      id="switch-orange"
      class="odpv switch switch--orange"
      type="checkbox"
    />
  </section>
</template>

<script>
export default {
  data() {
    return {
      check: true,
    };
  },
};
</script>
