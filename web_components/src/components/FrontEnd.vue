<template>
    <div class="container cont1">

       <div class="container-sm cont2">
            <img src="../images/desktop-image.png">
       </div>

       <div class="container cont3 ">
            <img src="../images/desktop-logo.svg">
       </div>

       <div class="container-sm cont4">
            <h2>Join us for a coffee or late night cocktails?</h2>
            <p>Please verify that you are 18 years of age or older to enter the site.</p>

            <button class="btn btn-dark">Enter Site</button>
       </div>
    </div>
</template>

<style>
    .cont1 {
        width: 30%;
        background-image: url("../images/desktop-background.svg");
        height: 80vh;
      
    }

    .cont2 {
        display: flex;
     
        height: 60vh;
        width: 30%;
        margin-top: 5%;
        background-repeat: no-repeat;
    }

    .cont3 {
       
       position:relative;
       left: 30%;
       top: -75%;
    }

    .cont4 {
        background: #FFFFFF 0% 0% no-repeat padding-box;;
        margin-top: -20%;
        width: 30%;
        display: block;
    }

    h2 {
        text-align: left;
        font: normal normal bold 48px/72px Helvetica;
    }

    p {
        font: oblique normal normal 20px/30px Helvetica;
    }

    button {
        display: flex;
    
    }
</style>