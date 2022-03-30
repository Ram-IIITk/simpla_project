<template>
    <div class="container9">
        <div class="con-9-lo">
            <div class="icon-f">
                <img  src="./../assets/image/twitter-16.png">
                <img class="u" src="./../assets/image/fb.png">
            </div>
        </div>
        <div class="con-9-row-1">
            <p>Products</p>
            <p>Our Science</p>
            <p>Vision & Mission</p>
            <p>About Us</p>
        </div>
        <div class="con-9-row-2">
            <hr>
            <div class="foot-s">
                <p>Subscribe to our Newsletter</p>
            </div>

            <div class="foot-box">
                <input>
                <a>Activate</a>
            </div>
        </div>
    </div>
</template>


<style scoped>
.ic{
    display: block;
    width: 100%;
    padding: 10px;
}
.con-9-row-1{
    padding-bottom:  20px;
    display: block;
    padding-top: 50px;
}

.con-9-row-2{
    padding-bottom: 10px;
}

.foot{
    display: flex;
    float: right;
}
.foot-s{
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 300;
    font-size: 9.94737px;
    line-height: 206.5%;
}

.foot-box{
    margin-top: 2pc;
    justify-items: center;
    display: flex;
    justify-content: center;
    padding-left: 10px;
}

.foot-box a{
    padding-left: 20px;
}

.icon-f{
    float: right;
    display: flex;
    margin-right: 10px;

}

.icon-f img{
    padding: 10px;
    margin-top: 20px;
    margin-right: 10px;
}

</style>

<script>
export default {
  name: 'footer1',
  components: {
    
  }
}
</script>