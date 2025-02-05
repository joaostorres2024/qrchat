<template>
    <header>
        <a href="../App.vue"><div class="header-container">
            <img class="logo" src="../assets/logo.png" alt="Logo QR Chat">
            <h3 class="qr-text">QR Chat.<span class="green">io</span></h3>
        </div></a>
    </header>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Open+Sans:ital,wght@0,300..800;1,300..800&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Raleway:ital,wght@0,100..900;1,100..900&display=swap');

 *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
 }

 .logo{
    width: 80px;
 }

 .header-container{
    height: 90px;
    box-shadow: 0px 2px 30px rgb(0, 0, 0, 0.2);
    padding: 0 40px;
    background-color: #FCFCFC;
    align-items: center ;
    display: flex;
 }

 .qr-text{
    font-size: 30px;
    color: #0B0B0D;
 }

 .green{
    color: #23E7C0;
 }

 a{
    text-decoration: none;
 }
</style>

<script>

</script>