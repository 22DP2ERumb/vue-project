<template>
    <div class="img-container">

        <img class="main-img" src="/images/Car_example1.jpg" alt="">

        <div class="small-img-container">
            <a href=""><img class="small-img" src="/images/Car_example1.jpg" alt=""></a>
            <a href=""><img class="small-img" src="/images/Car_example1.jpg" alt=""></a>
            <a href=""><img class="small-img" src="/images/Car_example1.jpg" alt=""></a>
            <a href=""><img class="small-img" src="/images/Car_example1.jpg" alt=""></a>
            <a href=""><img class="small-img" src="/images/Car_example1.jpg" alt=""></a>
        </div>

        <div class="contact-info">
            <ul>
                <li>Number: <span>+23453453</span></li>
                <li>E-mail: <span>Janis@Guntars.com</span></li>
                <li>Place: <span>Tvaika Iela, Riga</span></li>
            </ul>
        </div>
    </div>
</template>
<style>
    .img-container{
        display: flex;
        flex-direction: column;
        position: relative;
        flex: 1;
    }

    .main-img{
        border: black solid 3px;
        border-radius: 5px;
        width: 750px;
        height: 500px;
    }

    .small-img-container{
        display: flex;
        flex-direction: row;
        width: 750px;
        overflow-x: scroll;
    }

    .small-img{
        border: black solid 3px;
        border-radius: 5px;
        width: 150px;
        height: 100px;
        margin: 10px;
    }

    .cardPage-info{
        display: flex;
        flex: 1;
        flex-flow: column;
        justify-content: center;
    }
</style>