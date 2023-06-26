<script setup>
    const openCarousel = function () {
        console.log('Ok')
    }

    


</script>

<template>
    <div v-on:click="openCarousel" class="dropdown-wrapper">
        <div class="dropdown-container">
            <div class="dropdown-item">
                <div class="flag">
                    <img src="../assets/sgd.png" alt="flag">
                </div>
                <div class="country-code">
                    <p>SGD</p>
                </div>
            </div>
            <!-- <div class="dropdown-item">
                <div class="flag">
                    <img src="../assets/usa.png" alt="flag">
                </div>
                <div class="country-code">
                    <p>USA</p>
                </div>
            </div> -->
        </div>

        <div class="dropdown-arrow">
            <img src="../assets/arrow.svg" alt="arrow">
        </div>

    </div>
</template>

<style scoped>
.dropdown-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    cursor: pointer;
}

.dropdown-container {}

.dropdown-item {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.country-code {
    padding-left: 13px;
    color: #26278D;
    font-size: 20px;
    font-family: Roboto;
    font-weight: 500;
}

.dropdown-arrow {
    padding-left: 5px;
    width: 24px;
    height: 24px;
    cursor: pointer;
}

.dropdown-arrow {
    max-width: 100%;
}
</style>