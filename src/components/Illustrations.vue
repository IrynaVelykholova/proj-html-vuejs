<script>
export default {
    components: {
    },
    
} 
</script>

<template>

<div class="container-fluid d-flex flex-wrap">
    <div class="row">
        <div class="immagine-container col-4">
            <img src="../assets/img/h-2-port-img-1.jpg" alt="Immagine 1">
            <div class="scritta">
                <h3>All these illustration</h3>
                <p>Illustration</p>
            </div>
        </div>
        
        <div class="immagine-container col-4">
            <img src="../assets/img/h-2-port-img-2.jpg" alt="Immagine 2">
            <div class="scritta">
                <h3>Type and illustrations</h3>
                <p>Illustration</p>
            </div>
        </div>
        
        <div class="immagine-container col-4">
            <img src="../assets/img/h-2-port-img-3.jpg" alt="Immagine 3">
            <div class="scritta">
                <h3>Draw and illustrate</h3>
                <p>Illustration</p>
            </div>
        </div>

        <div class="immagine-container col-4">
            <img src="../assets/img/h-2-port-img-4.jpg" alt="Immagine 3">
            <div class="scritta">
                <h3>Illustrations of novels</h3>
                <p>Illustration</p>
            </div>
        </div>

        <div class="immagine-container col-4">
            <img src="../assets/img/h-2-port-img-5.jpg" alt="Immagine 3">
            <div class="scritta">
                <h3>Too many illustrations</h3>
                <p>Illustration</p>
            </div>
        </div>

        <div class="immagine-container col-4">
            <img src="../assets/img/h-2-port-img-6.jpg" alt="Immagine 3">
            <div class="scritta">
                <h3>Dreams are illustrations</h3>
                <p>Illustration</p>
            </div>
        </div>
    </div>
</div>



</template>
<style lang="scss" scoped>

.container-fluid {
    margin-bottom: 100px;
}
.row > * {
    padding-right: 0;
    padding-left: 0;
}

.immagine-container {
    position: relative; /* Per posizionare la scritta all'interno del contenitore */
    overflow: hidden;
}

.immagine-container img {
    width: 100%;
    height: auto;
}

.scritta {
    position: absolute; 
    top: 45%;
    background-color: white;
    padding: 10px;
    opacity: 0; 
    transition: opacity 0.5s; 
    padding: 1rem 2rem;
}

.immagine-container:hover .scritta {
    opacity: 1; 
}
.scritta p {
    font-style: italic;
}


</style>
