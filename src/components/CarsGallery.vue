<template>
    <div>
        Gallery

        <CarCard />
        <CarCard />
        <CarCard />
        <CarCard />
    </div>
</template>

<script setup>
import CarCard from '@/components/parts/CarCard.vue';
</script>

<style lang="scss" scoped>
div {
    background-color: #fff;
}
</style>