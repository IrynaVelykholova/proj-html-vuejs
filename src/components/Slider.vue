<script>
export default  {
    components: {
    }
} 
</script>

<template>
    <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active d-flex" data-bs-interval="10000">
                <div class="text-slider">
                    <h1 class="title-slider">Projects made <br>with <span class="font-particular">love</span></h1>
                    <p class="p-slider">Neque porro quisquam est, qui colorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi.</p>
                    <button class="button-slider">READ MORE</button>
                </div>
                
                <img src="../assets/img/short-slider-rev-1-img-3.png" class="d-block img-slider" alt="...">
                <div class="img-foglia"><img src="../assets/img/short-slider-rev-1-img-9.png" alt=""></div>
                <div class="rosa-destro"><img src="../assets/img/short-slider-rev-1-img-6.png" alt=""></div>
                <div class="rosa-sinistro"><img src="../assets/img/short-slider-rev-1-img-2.png" alt=""></div>
                <div class="cespuglio"><img src="../assets/img/short-slider-rev-1-img-1.png" alt=""></div>
                <div class="erba-scura"><img src="../assets/img/short-slider-rev-1-img-7.png" alt=""></div>
                <div class="erba-verde"><img src="../assets/img/short-slider-rev-1-img-8.png" alt=""></div>
                <div class="foglia-rosa"><img src="../assets/img/short-slider-rev-1-img-10.png" alt=""></div>
                <div class="nuvola-verde"><img src="../assets/img/short-slider-rev-1-img-5.png" alt=""></div>
                <div class="nuvola-rosa"><img src="../assets/img/short-slider-rev-1-img-4.png" alt=""></div>


                
            </div>
        </div>

        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
        </button>
</div>
</template>
<style lang="scss" scoped>
#carouselExampleInterval {
    font-family: Arial, Helvetica, sans-serif;
    margin-top: 60px;
    margin-bottom: 150px;
    .font-particular {
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    .title-slider {
    font-size: 80px;
    }
    .p-slider {
    font-size: 25px;
    color: #878787;
    }
    .carousel-control-prev-icon, .carousel-control-next-icon {
    background-color: #f3d0c7;
    border-radius: 50%;
    }
    .carousel-control-prev-icon {
        margin-right: 120px;
    }
    .carousel-control-next-icon {
        margin-left: 120px;
    }
    .text-slider {
        margin-left: 150px;
        width: 800px;
    }
    .img-slider {
        margin-left: 50px;
        width: 500px;
    }
    .button-slider {
        padding: 15px 35px;
        margin-top: 1rem;
        border: 3px solid #f3d0c7;
        background-color: white;
        &:hover {
                color: white;
                background-color: #f3d0c7;
        }
    }
    .img-foglia {
        position: absolute;
        top: 50%;
        right: 150px;
    }
    .rosa-destro {
        position: absolute;
        top: 30%;
        right: 250px;
    }
    .rosa-sinistro {
        position: absolute;
        top: 25%;
        right: 43%;
    }
    .cespuglio {
        position: absolute;
        top: 71%;
        right: 45%;
    }
    .erba-scura {
        position: absolute;
        top: 80%;
        right: 41%;
    }
    .erba-verde {
        position: absolute;
        top: 75%;
        right: 15%;
    }
    .foglia-rosa {
        position: absolute;
        top: 82%;
        right: 5%;
    }
    .nuvola-verde {
        position: absolute;
        top: 10%;
        right: 5%;
    }
    .nuvola-rosa {
        position: absolute;
        top: 12%;
        right: 9%;
    }
}

</style>
