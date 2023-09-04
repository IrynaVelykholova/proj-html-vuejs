<script>
export default {
    components: {
    }
} 
</script>

<template>
    <div class="container-fluid text-center">
        <h2>Want to work with us? Send us <span class="message">a <br> message!</span></h2>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Excepturi ipsa quaerat ullam pariatur! Alias a impedit earum eos saepe! Id mollitia soluta saepe consectetur quasi quod assumenda a nobis voluptatum!</p>

        <button class="button-contact">CONTACT</button>
    </div>
</template>
<style lang="scss" scoped>
.container-fluid {
    background-image: url("../assets/img/h-2-background-1.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    height: 600px;
    font-family: Arial, Helvetica, sans-serif;
    margin-bottom: 140px;
}
.message {
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.container-fluid h2 {
    font-size: 70px;
    padding-top: 150px;
}
.container-fluid p {
    color: #878787;
    font-size: 20px;
    padding: 20px 200px;
}
.button-contact {
    padding: 15px 50px;
    margin-top: 1rem;
    border: none;
    background-color: #c0e1cf;
    &:hover {
        color: white;
        background-color: #f3d0c7;
    }
}
</style>
