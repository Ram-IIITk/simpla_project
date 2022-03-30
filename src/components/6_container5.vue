<template>
    <div class="container5">
        <div class="col5-row1">
            <p>Track your mood</p>
        </div>
        <div class="col5-row2">
            <p>All days and all moods are not made equal. But we can only improve what we measure. Track your mood and vitals (including skin and hair health) so you can take better care of yourself every day.</p>
        </div>
        <div class="col5-row3">
            <p>Track you mood on the app</p>
        </div>
        <div class="row">
            <div class="col">
                <img src="./../assets/image/img2-1.png" class="img-row">
                <img src="./../assets/image/img2-2.png" class="img-row">
            </div>

            <div class="col">
                <img src="./../assets/image/img2-3.png" class="img-row">
                <img src="./../assets/image/img2-4.png" class="img-row">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'container5',
    components: {
    
  }
}
</script>

<style>
.col5-row1{
    font-family: 'Reptile';
    font-style: normal;
    font-size: 32px;
    color: #000000;
}

.col5-row2{
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 300;
    font-size: 16px;
    line-height: 206.5%;
}

.col5-row3{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 15px 15px;
    width: 250px;
    height: 30px;
    background: linear-gradient(288.62deg, #6E8CF6 42.36%, rgba(110, 213, 246, 0.93) 115.74%);
    box-shadow: 0px 2px 16px rgba(71, 222, 255, 0.33);
    border-radius: 70px;
    margin-left: 10%;
    margin-top: 20px;
    margin-bottom: 20px;
    color: #ffffff;
}

.con-4-img{
    display: block;
    margin-left: auto;
    margin-right: auto;
}

.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create two equal columns that sits next to each other */
.col {
  flex: 40%;
  padding: 0 4px;
}
.col img {
  margin-top: 8px;
  vertical-align: middle;
}


</style>