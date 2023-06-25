<script setup>
import TitleApp from './components/TitleApp.vue'
import CurrencyInput from './components/CurrencyInput.vue';
</script>

<template>
  <div class="wrapper">
    <TitleApp />
    <CurrencyInput />
  </div>
</template>

<style>
.wrapper {
  max-width: 100%;
  margin: 0 auto;
  padding: 20px 15px 20px 15px;
  background-color: #F6F6F6;
  border-radius: 14px;
}
</style>
