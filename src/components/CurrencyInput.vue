<script setup>
import { ref } from 'vue'

const numbers = ref();

</script>

<template>
    <input v-model="numbers" class="input-currency" type="number">
    <p> {{ numbers }}</p>
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
    margin: 0 0 0 8px;
    text-align: end;
    padding: 11px 14px;
    outline: none;
    border: none;
    max-width: 100%;
    font-family: Roboto;
    font-size: 20px;
    color: #3C3C3C;
    border-radius: 7px;
    background: #EFEFEF;
}
</style>