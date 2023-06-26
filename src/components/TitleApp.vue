<template>
    <!-- HTML-шаблон компонента -->
    <div class="text-title">
        <h1>{{ message }}</h1>
        <p class="subtitle">{{ subtitle }}</p>
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            message: 'Currency Converter',
            subtitle: 'Check live rates, set rate alerts, receive notifications and more.'
        }
    }
}
</script>
  
<style scoped>
/* CSS-стили компонента */
h1 {
    font-family: Roboto;
    color: #1F2261;
    font-size: 25px;
    text-align: center;
    font-weight: 700;
}

.subtitle {
    color: #808080;
    text-align: center;
    font-size: 16px;
    font-family: Roboto;
}
</style>