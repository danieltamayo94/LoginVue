<template>
  <section class="container">
    <h1>Iniciar Sesión</h1>
    <form action="#" id="login">
      <InputField id="email" type="email" placeholder="correo@correo.com" label="Correo Electrónico"></InputField>
      <InputField id="password" type="password" placeholder="*****" label="Contraseña"></InputField>
      <ButtonInput msgButton="Enviar"></ButtonInput>
    </form>
  </section>
</template>

<script>
import InputField from './Shared/InputField.vue';
import ButtonInput from './Shared/ButtonInput.vue';

export default {
  name: 'UserLogin',
  props: {
    msgButton: String
  },
  components: {
    InputField,
    ButtonInput
  }
}
</script>

<style src="../assets/css/styles.css"></style>
