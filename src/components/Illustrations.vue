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
                <div>All these illustration</div>
                <div>Illustration</div>
            </div>
        </div>
        
        <div class="immagine-container col-4">
            <img src="../assets/img/h-2-port-img-2.jpg" alt="Immagine 2">
            <div class="scritta">
                <div>Type and illustrations</div>
                <div>Illustration</div>
            </div>
        </div>
        
        <div class="immagine-container col-4">
            <img src="../assets/img/h-2-port-img-3.jpg" alt="Immagine 3">
            <div class="scritta">
                <div>Draw and illustrate</div>
                <div>Illustration</div>
            </div>
        </div>

        <div class="immagine-container col-4">
            <img src="../assets/img/h-2-port-img-4.jpg" alt="Immagine 3">
            <div class="scritta">
                <div>Illustrations of novels</div>
                <div>Illustration</div>
            </div>
        </div>

        <div class="immagine-container col-4">
            <img src="../assets/img/h-2-port-img-5.jpg" alt="Immagine 3">
            <div class="scritta">
                <div>Too many illustrations</div>
                <div>Illustration</div>
            </div>
        </div>

        <div class="immagine-container col-4">
            <img src="../assets/img/h-2-port-img-6.jpg" alt="Immagine 3">
            <div class="scritta">
                <div>Dreams are illustrations</div>
                <div>Illustration</div>
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
    position: absolute; /* Posiziona la scritta sopra l'immagine */
    top: 50%;
    background-color: white;
    text-align: center;
    padding: 10px;
    opacity: 0; /* Inizialmente, la scritta è nascosta */
    transition: opacity 0.3s; /* Aggiunge una transizione per l'opacità */
}

/* Mostra la scritta su hover */
.immagine-container:hover .scritta {
    opacity: 1; /* Mostra la scritta quando passi il mouse sopra il contenitore */
}


</style>
