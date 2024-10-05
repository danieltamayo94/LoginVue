<template>
    <div class="inputContainer">
      <label :for="inputId">{{ label }}</label>
      <input :id="inputId" :type="type" :placeholder="placeholder" :name="inputId" />

    </div>
  </template>

<script>
export default {
  name: 'InputField',
  props: {
    type: {
      type: String,
      default: 'text'
    },
    placeholder: {
      type: String,
      default: ''
    },
    label: {
      type: String,
      default: 'Etiqueta'
    },
    inputId: {
      type: String,
      required: true
    }
  }
}
</script>