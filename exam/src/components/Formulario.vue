<template>
  <div>
    <h2>Formulario Itca</h2>
    <form>
      <div>
        <label for="nombre">Nombre Completo</label>
        <input id="nombre" type="text" placeholder="Ingresa tu nombre" />
      </div>

      <div>
        <label for="apellido">Apellido</label>
        <input id="apellido" type="text" placeholder="Ingresa tu apellido" />
      </div>

      <div>
        <label for="carnet">Carnet</label>
        <input id="carnet" type="text" placeholder="20250001" />
      </div>

      <div>
        <label for="edad">Edad</label>
        <input id="edad" type="number" placeholder="Ingresa tu edad" />
      </div>

      <div>
        <label for="edad">Dui</label>
        <input id="edad" type="number" placeholder="Ingresa tu dui" />
      </div>

      <button type="submit">Enviar</button>
    </form>
  </div>
</template>

<script setup>
</script>

<style scoped>
  form {
    display: flex;
    flex-direction: column;
    gap: 12px;
    max-width: 300px;
  }

  label {
    font-weight: 600;
    margin-bottom: 4px;
  }

  input {
    padding: 6px;
    border: 1px solid #ccc;
    border-radius: 6px;
  }

  button {
    padding: 8px 12px;
    border: none;
    border-radius: 6px;
    background: #2b84ff;
    color: white;
    cursor: pointer;
  }

  button:hover {
    background: #1a5fd0;
  }
</style>
