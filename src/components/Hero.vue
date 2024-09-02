<template>
        <div class="hero-wrapper">
                <div class="hero-slide">
                        <div>
                            <figure>
                                <img src="../assets/imgs/banner-img-1.png" alt="">
                            </figure> 
                        </div>
                        <div>
                            <figure>
                                <img src="../assets/imgs/banner-img-1.png" alt="">
                            </figure> 
                        </div>
                               
                </div>
                <div class="container"> 
                    <div class="hero-title ">
                        <h3>New creators on the block</h3>
                        <p>In case you thought we only did tees...Discover totes, caps, prints and more designed by the best grassroots creators out there. </p>
                        <span class="btn-shop"><a href="#">Shop Editor's pick</a></span>
                    </div>
                </div>

        </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.hero-wrapper{
    width: 100%;
    height: 90vh;
    position: relative;
    overflow: hidden;
}

.hero-slide{
    display: flex;
    overflow: hidden;
    width: 200vw;
    height: 100%;

    div figure img {
          width: 100vw;
          height: 100vh;
          object-fit: cover;
            
    }

}

.hero-title{
    position: absolute;
    z-index: 10;
    bottom: 50px;
    color: white;
    h3{
     
          text-transform: uppercase;  
       
    }
    p{
        font-size: 13px;
        width: 60%;
    }
}
.btn-shop{
    background-color: white;
    color: rgb(131, 131, 131);
    padding: 1rem 2rem;
    font-family: 'Helvetica Neue';
    font-weight: 400;
    text-transform: uppercase;
}
</style>