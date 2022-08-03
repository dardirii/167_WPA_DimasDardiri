<template>
  <div id="testimonial" class="testimonial section-padding">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="section-header text-center pb-5">
            <h2>Testimonial</h2>
            <p>
              Lorem ipsum dolor, sit amet consectetur <br />adipisicing elit.
              Inventore, in!
            </p>
          </div>
        </div>
      </div>
      <div class="row">
          <div v-for="(item, index) in testimonial" :key="index" class="col-12 col-md-3 col-lg-3">
            <div class="card text-center">
              <div class="card-body">
                <p class="card-text fst-italic fw-light">
                  {{ item.message }}
                </p>
                <img
                  :src="item.avatar"
                  alt=""
                  class="img-fluid rounded-circle"
                />
                <h4 class="card-title pt-3 fw-bold">{{ item.name }}</h4>
                <p class="fst-italic">{{ item.designation }}</p>
              </div>
            </div>
          </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.section-padding {
  padding: 100px 0;
}
.card{
  height : 500px;
  border-radius: 0;
  box-shadow: 15px 15px 40px rgba(0,0,0,0.15)
}

@media only screen and (max-width: 767px){
    .card{
        height: 450px;
        margin: 10px 0;
    }
}
</style>

<script>
export default {
  data() {
    return {
      testimonial: [],
    };
  },
  mounted() {
    fetch("https://testimonialapi.toolcarton.com/api")
      .then((res) => res.json())
      .then((res) => {
        this.testimonial = res.slice(0, 4);
      });
  },
};
</script>
