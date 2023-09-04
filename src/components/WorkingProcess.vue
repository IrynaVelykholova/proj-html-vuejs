<script>
export default {
    components: {
    }
} 
</script>

<template>
    <div class="container">
        <h2 class="text-center working">Working <span class="process">Process</span></h2>
        <div class="d-flex justify-content-center">
            <img src="../assets/svg/svg-3.svg" alt="">
        </div>
        <!-- icone -->
        <i class="fa-solid fa-lightbulb fa-3x lampadina"></i>
        <i class="fa-regular fa-comment fa-3x commento"></i>
        <i class="fa-solid fa-cloud fa-3x nuvola"></i>
        <i class="fa-solid fa-pencil fa-3x matita"></i>

        <div class="row">
            <div class="col-3 px-3 text-center">
                <div>
                    <h5>First theres an idea</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia cum fugit sed quod!</p>
                </div>
            </div>
            <div class="col-3 px-3 text-center">
                <div>
                    <h5>Then we talk about</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia cum fugit sed quod! </p>
                </div>
            </div>
            <div class="col-3 px-3 text-center">
                <div>
                    <h5>And we think about</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia cum fugit sed quod! </p>
                </div>
            </div>
            <div class="col-3 px-3 text-center">
                <div>
                    <h5>So we draw alog</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia cum fugit sed quod! </p>
                </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.container {
    font-family: Arial, Helvetica, sans-serif;
    position: relative;
    margin-bottom: 120px;
}
.working {
    font-size: 70px;
    margin-bottom: 70px;
}
.process {
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.col-3 p {
    color: #878787;
}
.col-3 h5 {
    font-size: 20px;
}
.lampadina {
    position: absolute;
    left: 84px;
    top: 160px;
    color: #d8f0e3;
}
.commento {
    position: absolute;
    left: 400px;
    top: 160px;
    color: yellow;
}
.nuvola {
    position: absolute;
    right: 400px;
    top: 160px;
    color: #80465f;
}
.matita {
    position: absolute;
    right: 80px;
    top: 160px;
    color: #eb6950;
}
img {
    margin-bottom: 70px;
}
</style>
