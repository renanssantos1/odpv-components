<template>
  <header class="odpv header">
    <nav>
      <ul>
        <li>
          <ul>
            <a href="#">Formulário</a>
            <li>Input</li>
            <li>Checkbox</li>
            <li>Validação</li>
            <li>Switch</li>
            <li>Alertas</li>
          </ul>
        </li>
      </ul>
    </nav>

    <div>
      <button>Menu</button>
    </div>
    <aside class="odpv header--aside">
      <ul>
        <li v-for="i in 6" :key="i">Item de menu {{ i }}</li>
      </ul>
    </aside>
  </header>
</template>

<script>
export default {};
</script>
