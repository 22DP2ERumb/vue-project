<template>
    <div class="cardPage-info">
            <h2><img class="car-logo" src="/images/Car_logo_example.png">Audi Q3</h2>
            <div class="carPage-specifications">
                <ul>
                    <li>Year: <span>1978</span></li>
                    <li>Engine: <span>0.5</span></li>
                    <li>Fuel Type: <span>Tvaiks</span></li>
                    <li>Transimiton: <span>Nav</span></li>
                    <li>Drive Type: <span>Kājas</span></li>
                    <li>Mileage: <span>-100000000</span></li>
                    <li>Color: <span>Spainis</span></li>
                    <li>Body Type: <span>Sedans</span></li>
                    <li>Seating Capacity: <span>4</span></li>
                    <li>Fuel Efficincy: <span>0</span></li>
                    <li>Emissions Class: <span>EURO 999</span></li>
                    <li>Condiion: <span>NEW</span></li>
                    <li>VIN Number: <span>2134234234234asda</span></li>
                </ul>
            </div>
            <div class="cardPage-betting-info">
                <h2>Highest Bid: <span>3000$</span></h2>
            </div>
            <div class="cardPage-betting-info-small">
                <p>Started: <span>3000$</span></p>
                <p>Buy-out: <span>15000$</span></p>
                <p>Time: <span></span></p>
            </div>
            <div class="cardPage-betting">
                <button>Bid</button>

            </div>
        </div>
</template>
<style>
    
    .cardPage-info{
    display: flex;
    flex: 1;
    flex-flow: column;
    justify-content: center;
    }
    .carPage-specifications{
        margin-top: 80px;
        
    }

    .carPage-specifications li {
        font-size: 15px;
        color: #555;
        display: flex;
        justify-content: space-between;
        padding: 10px 0;
        border-bottom: 1px solid #ddd;
        margin-left: -70px;
        position: relative;
    }

    .carPage-specifications li span {
        font-weight: bold;
        color: #333;
        position: absolute;
        left: 50%;
    }

    .cardPage-info h2{
        margin: 0;
    }

    .contact-info {
        margin-top: 100px;
    }
    .contact-info li{
        margin: 5px;
        color: gray;
        font-size: 20px;
    }

    .contact-info li span{
        color: black;
        font-size: 20px;
    }
    .cardPage-betting-info{
        display: flex;
        flex-flow: row;
        justify-content: center;
        margin: 20px;
        margin-bottom: 0px;
        
    }
    .cardPage-betting-info h2 {
        margin: 30px;
        margin-bottom: 15px;
    }

    .cardPage-betting-info h2 span{
        color: green;
        
    }

    .cardPage-betting-info-small{
        display: flex;
        flex-flow: column;
        justify-content: center;
        margin-top: -15px;
        margin-bottom: 30px;
    }
    .cardPage-betting-info-small span{
        color: green;
        font-weight: bold;
    }
    .cardPage-betting-info-small p{
        font-style: italic;
        font-weight: bold;
        text-align: center;
        margin: 0px;
        
    }

    .cardPage-betting{
        display: flex;
        justify-content: center;
    }
    .cardPage-betting button{
        margin-top: 0px;
        width: 200px;
        height: 60px;
        background-color: darkgreen;
        color: white;
        font-weight: bold;
        font-size: 24px;
        border-radius: 5px;
        cursor: pointer;
    }
</style>