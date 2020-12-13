<template>
        <div class="tarjetas">
            <div class="card" style="width: 18rem;">
                <img src="img/imagen2.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Mansión 1</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    <a href="#" class="btn btn-primary">Ver Propiedad</a>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <img src="img/imagen3.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Mansión 2</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    <a href="#" class="btn btn-primary">Ver Propiedad</a>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <img src="img/imagen4.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Mansión 3</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    <a href="#" class="btn btn-primary">Ver Propiedad</a>
                </div>
            </div>

        </div>
</template>
<script>
export default {
    name: 'Contenido',
}
</script>

<style>
    .tarjetas{
        margin-top: 50px;
        margin-bottom: 50px;
        justify-items: center;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-template-rows: 1fr;
    }
</style>