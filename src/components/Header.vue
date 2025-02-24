style
<template>
  <header>
    <nav>
        <RouterLink to="/" class="logo-container">
            <img src="/images/car_logo.png" alt="">
            <h1 class="site-name">AutoIzsole.lv</h1>
        </RouterLink>       
        <ul>
            <li><RouterLink to="/">Brand's</RouterLink></li>
            <li><RouterLink to="/">About Us</RouterLink></li>
            <li><RouterLink to="/">Contact Us</RouterLink></li>
        </ul>   
        <ul class="auth-links">
            <li><RouterLink to="/login">Login</RouterLink></li>
            <li><RouterLink to="/">Register</RouterLink></li>
        </ul>


        
    </nav>
  </header>
</template>

<style>
header {
    border-bottom: 2px solid black;
    width: 100%;
}
nav {
    display: flex;
    align-items: center;
}
nav ul{
    display: flex;
}
nav li{
    margin: 20px;
    transition: transform 0.3s ease, color 0.3s ease;
}
nav li a {
    font-weight: bold;
}
nav li:hover {
    transform: scale(1.2);
}
nav li a.active {
    border-bottom: 2px solid black;
}
.logo-container{
    margin: 10px;
    display: flex;
    align-items: center;
}
.logo-container img{
    width: 60px;
    height: auto;
}
.site-name {
    font-size: 25px;
    font-weight: bold;
    margin: 10px;
}
nav .auth-links {
    margin-left: auto;
}
@media (max-width: 768px) {
    nav ul, nav .auth-links {
        display: none;
    }
    nav {
        justify-content: center;
    }
    
    .sidebar {
        display: block;
    }

    .sidebar-button {
        transform: translateX(0);
    }
    .card{
        width: 300px;
        height: 400px;
    }
}
</style>