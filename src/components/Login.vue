<template>
    <form action="">

        <img src="/images/car_logo.png" alt="">
        <h1 class="site-name">AutoIzsole.lv</h1>

        <input type="text" placeholder="E-mail">
        <input type="password" placeholder="Password">
        <button type="submit"><span class="material-symbols-outlined">login</span></button>
    </form>
</template>
<style>
    .login form{
        width: 100%;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        font-size: 30px;
        
    }

    .login input{
        width: 100%;
        height: 30px;
        margin-top: 10px;
    }

    .login button{
        margin-top: 40px;
        border: none;
        background-color: transparent;
        transition: background-color 0.3s ease;
        transition: box-shadow 0.3s ease;
        cursor: pointer;

    }

    .login button:hover{
        border-radius: 3px;
        background-color: #e0e0e0;
        box-shadow: 0 0 0 2px rgb(0, 0, 0);
        color: rgb(45, 45, 211);
    }
</style>