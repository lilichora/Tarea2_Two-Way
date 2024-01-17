
<template>
  <div style="background-color: aquamarine;">
    <body>
      <p style="color: blue;">Ingresar nombre</p>
      <input type="text" v-model="message">
      <p >Este Trabajo fue realizado por el grupo 6 y sus Integrantes son :</p><p style="color: red;"> {{ message }}</p><p> Y nosotros aprendimos la funcion TwoWayBinding</p>
    </body>
  </div>
</template>

<script >
export default {
  data() {
    return {
      message: 'Liliana Chora, Ivonne Jacome, Douglas Moreno '
    };
  }
};
</script>
