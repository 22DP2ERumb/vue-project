<script setup>
    import LeftCarContainer from './LeftCarContainer.vue'
    import RightCarContainer from './RightCarContainer.vue'
</script>

<template>
    <div class="CardPage-container">
        <LeftCarContainer/>
        <RightCarContainer/>
    </div>
</template>

<style>
    .CardPage-container{
        margin: 20px;
        display: flex;
        flex-direction: row;
        position: relative;
    }
</style>