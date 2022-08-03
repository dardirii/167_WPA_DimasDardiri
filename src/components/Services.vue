<template>
    <div id="services" class="services section-padding">
        <div class="container">
            <div class="row">
                <div class="col-md-12">
                    <div class="section-header text-center pb-5">
                        <h2>Our Services</h2>
                        <p>Lorem ipsum dolor, sit amet consectetur <br>adipisicing elit. Inventore, in!</p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12 col-md-12 col-lg-4">
                    <div class="card text-white text-center bg-dark pb-2">
                        <div class="card-body">
                            <i class="bi bi-subtract"></i>
                            <h3 class="card-title">Best Quality</h3>
                            <p class="lead">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Temporibus perspiciatis voluptates vel, perferendis officiis, voluptatibus non culpa iste praesentium quis aliquam placeat quasi cumque incidunt!</p>
                            <button class="btn btn-warning text-dark">Read More</button>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-12 col-lg-4">
                    <div class="card text-white text-center bg-dark pb-2">
                        <div class="card-body">
                            <i class="bi bi-patch-check-fill"></i>
                            <h3 class="card-title">Integrity</h3>
                            <p class="lead">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Temporibus perspiciatis voluptates vel, perferendis officiis, voluptatibus non culpa iste praesentium quis aliquam placeat quasi cumque incidunt!</p>
                            <button class="btn btn-warning text-dark">Read More</button>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-12 col-lg-4">
                    <div class="card text-white text-center bg-dark pb-2">
                        <div class="card-body">
                            <i class="bi bi-gear-fill"></i>
                            <h3 class="card-title">Sustainabilty</h3>
                            <p class="lead">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Temporibus perspiciatis voluptates vel, perferendis officiis, voluptatibus non culpa iste praesentium quis aliquam placeat quasi cumque incidunt!</p>
                            <button class="btn btn-warning text-dark">Read More</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.section-padding {
    padding:100px 0;
}

.services .card-body i{
    font-size: 50px;
}
@media only screen and (max-width: 767px){
    .card{
        margin: 10px 0;
    }
}
</style>