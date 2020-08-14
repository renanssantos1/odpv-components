<template>
  <section>
    <div>
      <label class="odpv form__label" for="login-email">E-mail:</label>
      <input
        class="odpv form__control"
        type="email"
        id="login-email"
        name="login-email"
        placeholder="Ex.: email@email.com"
      />

      <div class="aph form__helper form__helper--error">
        This field is required and need a valid e-mail address
      </div>
    </div>

    <label class="odpv form__label">Name</label>
    <input class="odpv form__control" type="text" disabled placeholder="Name" />

    <input type="checkbox" class="odpv form__control" />
    <label class="odpv form__label" for="aceito-termos">
      Aceito os termos
    </label>

    <i class="fas fa-check"></i>
  </section>
</template>

<script>
export default {};
</script>

<style></style>
