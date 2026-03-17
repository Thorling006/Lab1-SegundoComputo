<script setup>
import { ref } from 'vue';
const nombre = ref('');
const apellido = ref('');
const correo = ref('');
const contraseña = ref('');

const registrarse = () => {
    console.log(nombre.value, apellido.value, correo.value, contraseña.value);
} 
</script>

<template>
    <input type="text" placeholder="Nombre">
    <input type="text" placeholder="Apellido">
    <input type="text" placeholder="Correo">
    <input type="text" placeholder="Contraseña">
    <button>Registrarse</button>
</template>

<style scoped>
    input {
        margin: 10px;
        padding: 10px;
    }
    button {
        margin: 10px;
        padding: 10px;
    }
</style>
