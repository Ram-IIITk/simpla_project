<template>
    <div class="container1">
        <div class="text-cen can-row1">
            <p>About Diana</p>
        </div>
        <div class="text-cen con-1-row2">
            <p>A platform that looks out for you</p>
        </div>
        <div class="coloum col-1-row3">
            <p >Diana empowers you to understand how your body works so you can look and feel your best. </p>
        </div>
        <hr>
        <div class="text-cen con1-row4">
            <p>Our Philosophy</p>
        </div>
        <div class="text-cen col1-row5">
            <p>Sustainable wellness is a big-picture, inside out approach</p>
        </div>
        <div class="text-cen col1-row6">
            <p>Diana is on a mission to create thoughtful, science-backed solutions for women who want to make informed decisions about their health and wellness.</p>
            <br>
            <p>That’s why we’ve created an integrated ecosystem of: </p>
        </div >
        <div>
            <img src="./../assets/image/Vector_1.png">
        </div>
        <div class="text-cen col1-row7">
            <p>Consciously formulated products that deliver feel-good results fast 
                <img class="con1-img"  src="../assets/image/Vector_2.png">
                In-app mood and period tracking options that help you cultivate a deeper connection with your mind and body 
                <img class="con1-img" src="../assets/image/phone.png">               
                In-app consultation portals that connect you with compassionate wellness experts </p>
        </div>
        <div class="text-cen col1-last">
            <p>Consider us your nerdy ally who spends their time perfecting products that work because they want you to feel your best everyday.</p>
        </div>
    </div>
</template>


<script>

export default {
  name: 'container1',
}
</script>

<style >

/*font*/
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500;600;900&display=swap');

.can-row1{
    font-family: 'Reptile';
    font-style: normal;
    font-weight: 500;
    font-size: 33px;
    line-height: 30px;  
    color: #1B1B50;
    padding-top: 70px;
}
.col-1-row3{
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 300;
    font-size: 14px;
    line-height: 179%;
}

.con-1-row2{
    font-family: 'Quicksand';
    font-style: normal;
    font-weight: 700;
    font-size: 18px;
    line-height: 22px;
    text-align: center;
    color: #1B1B50;
}

.con1-row4{
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 700;
    font-size: 22px;
    line-height: 33px;
    color: #1B1B50;    
}

.col1-row5{
    font-family: 'Reptile';
    font-style: normal;
    font-weight: 500;
    font-size: 33px;
    line-height: 134.8%; 
    color: #1B1B50;   
}

.col1-row6{
    font-family: 'DM Sans';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 179%;
    text-align: center;
    color: #1B1B50;
}

.col1-row7{
    padding-top: 10px;
    padding-bottom: 10px;
    color: #1B1B50;

}

.col1-last{

    font-family: 'DM Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 179%;
    text-align: center;
    color: #1B1B50;
    padding-bottom: 20px;
}

/*image*/

img{
      
    display: block;
    margin-left: auto;
    margin-right: auto;
    padding-top: 10px;
    padding-bottom: 10px;
      }

.con1-img{
    width: 20%;
}

</style>