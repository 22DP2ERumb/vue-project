<script setup>
    import CardDescription from './CardDescription.vue'
</script>
<template>
    <div class="card">
        <RouterLink to="/car">
            <img class="car-img" src="/images/Car_example1.jpg">
            <CardDescription/>

            <img class="car-logo" src="/images/Car_logo_example.png">
        </RouterLink>
    </div>
</template>
<style>
    .card{
    position: relative;
    display: flex;
    margin: 20px;
    width: 250px;
    height: 350px;
    border-radius: 2px;
    box-shadow: 0 0 0 2px black;
    transition: transform 0.3s ease, color 0.3s ease;
}
    .card:hover{
        transform: scale(1.2);
    }
    .car-img{
        width: 100%;
        height: 50%;
        border-bottom: 2px solid black;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
    }
    .car-logo {
        position: absolute;
        bottom: 10px;
        right: 10px;
        width: 45px;
        height: auto;
    }
</style>