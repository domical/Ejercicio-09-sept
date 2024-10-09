<template>
    <div>
    <input type="number" v-model="numero" placeholder="Ingresa un número" />
    <p>El número ingresado es: {{ numero }}</p>
    </div>
</template>

<script>
    export default {
    data() {
    return {
        numero: null
    };
    }
};
</script>

<style scoped>
input {
    padding: 10px;
    font-size: 16px;
    margin-bottom: 20px;
    width: 100%;
    max-width: 300px;
}

p {
    font-size: 18px;
}
</style>