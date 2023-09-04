<script>
export default {
    components: {
    }
} 
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-4">
                <div class="immagine-container">
                    <img src="../assets/img/h-2-blog-img-1.jpg" alt="">
                </div>
                    <h3 class="mt-4">This way, loves: a detailed guide through new design</h3>
                    <p>By Emily Fields</p>
            </div>
            <div class="col-4">
                    <div class="immagine-container">
                        <img src="../assets/img/h-2-blog-img-2.jpg" alt="">
                    </div>
                    <h3 class="mt-4">I try to give people a different way of looking art</h3>
                    <p>By Emily Fields</p>
            </div>
            <div class="col-4">
                    <div class="immagine-container">
                        <img src="../assets/img/h-2-blog-img-3.jpg" alt="">
                    </div>
                    <h3 class="mt-4">Introduce Richard Laperrière of those amazing features</h3>
                    <p>By Emily Fields</p>
            </div>
        </div>
        <img src="../assets//img/may-1.png" alt="" class="may img-1">
        <img src="../assets//img/may-2.png" alt="" class="may img-2">
        <img src="../assets//img/may-3.png" alt="" class="may img-3">
    </div>
</template>
<style lang="scss" scoped>
.container {
    font-family: Arial, Helvetica, sans-serif;
    margin-bottom: 120px;
    position: relative;
}
.col-4 img {
    width: 100%;
}
.col-4 p {
    font-style: italic;
}
.may {
    width: 60px;
}
.img-1 {
    position: absolute;
    top: -15px;
    left: 30px;
}
.img-2 {
    position: absolute;
    top: -15px;
    left: 470px;
}
.img-3 {
    position: absolute;
    top: -15px;
    right: 350px;
}
.immagine-container {
    overflow: hidden;
}
.immagine-container img {
    transition: transform 0.3s; 
}
.immagine-container:hover img {
    transform: scale(1.1); 
}
</style>
