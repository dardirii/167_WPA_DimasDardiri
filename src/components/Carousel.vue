<template>
    <div id="carouselExampleCaptions" class="carousel slide pt-3 mt-2" data-bs-ride="false">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="../assets/banner1.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption">
        <h5>Lets Get Started</h5>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quae impedit itaque nemo aspernatur non.</p>
        <p><a href="#" class="btn btn-warning mt-3">Learn More</a></p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="../assets/banner2.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption">
        <h5>Always Dedicated</h5>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quae impedit itaque nemo aspernatur non.</p>
        <p><a href="#" class="btn btn-warning mt-3">Learn More</a></p>
      </div>
    </div>
    <div class="carousel-item">
      <img src="../assets/banner3.jpg" class="d-block w-100" alt="...">
      <div class="carousel-caption">
        <h5>Lets Get Started</h5>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quae impedit itaque nemo aspernatur non.</p>
        <p><a href="#" class="btn btn-warning mt-3">Learn More</a></p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</template>

<style scoped>
.carousel-item{
    height: 100vh;
    min-height: 300px;
}
.carousel-caption{
    bottom: 200px;
    z-index: 2;
}
.carousel-caption h5{
    font-size:45px;
    text-transform: uppercase;
    letter-spacing: 2px;
    margin-top: 25px;
}
.carousel-caption p{
    width: 60%;
    margin: auto;
    font-size: 18px;
    line-height: 1.9;

}
.carousel-inner::before{
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    background: rgba(0,0,0,0.7);
    z-index:1;
}
@media only screen and (max-width: 767px){
    .carousel-caption{
        bottom:230px;
    }
    .carousel-caption h5{
        font-size: 17px;
    }
    .carousel-caption a{
        padding: 10px 15px;
        
    }
    .carousel-caption p{
        width:100%;
        line-height:1.6;
        font-size: 12px;
    }
    .carousel img{
      height: 100%;
      width: auto;
      object-fit: fill;
    }
}
</style>