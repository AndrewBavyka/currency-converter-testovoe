<script setup>
import { ref } from 'vue'

const numbers = ref();

</script>

<template>
    <input v-model="numbers" class="input-currency" type="number">
    <p>Сообщение {{ numbers }}</p>
</template>
    
<style scoped>
p {
    color: red;
}

/* Chrome, Safari, Edge, Opera */
input::-webkit-outer-spin-button,
input::-webkit-inner-spin-button {
    -webkit-appearance: none;
    margin: 0;
}

/* Firefox */
input[type=number] {
    -moz-appearance: textfield;
}

.input-currency {
    border: none;
    max-width: 100%;
    padding: 0 0 0 5px;
    font-family: Roboto;
    font-size: 20px;
    color: #3C3C3C;
    border-radius: 7px;
    background: #EFEFEF;
}
</style>