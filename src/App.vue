<script setup>
import TitleApp from './components/TitleApp.vue'
import CurrencyInput from './components/CurrencyInput.vue';
import CountryDropdown from './components/CountryDropdown.vue';
</script>

<template>
  <div class="wrapper">
    <TitleApp />
    <div class="block">
      <CountryDropdown />
      <CurrencyInput />
    </div>

    <!-- <div class="block">
      <CountryDropdown />
      <CurrencyInput />
    </div> -->
  </div>
</template>

<style>
.wrapper {
  max-width: 100%;
  margin: 0 auto;
  padding: 15px 20px;
  background-color: #F6F6F6;
  border-radius: 14px;
}

.block {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
