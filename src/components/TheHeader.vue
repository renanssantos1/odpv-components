<template>
  <header class="odpv header">
    <div>
      <img
        class="logo"
        src="https://ranek.origamid.dev/img/ranek.e7a4871b.svg"
        alt=""
      />
    </div>

    <div>
      <button @click="ativo = !ativo">abrir</button>
    </div>
    <aside
      class="odpv"
      :class="ativo ? 'header--aside-ativo' : ' header--aside'"
    >
      <ul>
        <button @click="ativo = !ativo">fechar</button>
        <li v-for="i in 6" :key="i">Item de menu {{ i }}</li>
      </ul>
    </aside>
  </header>
</template>

<script>
export default {
  data() {
    return {
      ativo: false,
    };
  },
};
</script>
