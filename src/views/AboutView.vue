<template>
  <div>
    <section class="hero-about">
      <div class="hero-image-about"></div>
    </section>
    <section class="main-content-about" style="background-color: #343a40;">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <br>
            <h2 class="section-title">About Us</h2> <br>
            <p class="section-text">
              Even after 25 years of work, we do not leave our guests indifferent.<br>
              <br>In addition to a large selection of pizzas, we also offer different <br> types of dishes - something for everyone. <br>
              <br>Someone will find themselves in pizza or pasta, someone in the <br> charcoal grill,  and we always have sweet surprises for those <br> with a sweet tooth.
              <br><br> So, come and enjoy with us!
            </p><p class="services">SERVICES: Meal in restaurant - Sitting on the terrace -  Curbside pickup</p>
          </div>
          <div class="col-md-6">
            <img src="../assets/abtus.jpg" alt="About Image" class="about-image">
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');

.container {
  max-width: 1400px;
  margin: 0 auto;
  padding: 0 15px;
}

.hero-about {
  position: relative;
  color: #fff;
  padding: 300px 0; 
  overflow: hidden;
}

.hero-image-about {
  background-image: url('/src/assets/pizza2.jpg');
  background-size: cover; 
  background-position: center;
  width: 100%;
  height: 100%; 
  position: absolute;
  top: 0;
  left: 0;
  animation: zoomIn 10s infinite alternate; 
}

@keyframes zoomIn {
  0% {
    transform: scale(1);
  }
  100% {
    transform: scale(1.1);
  }
}

.main-content-about {
  padding: 50px 0; 
  margin-bottom: 0; 
}

.section-title {
  font-size: 3rem;
  margin-bottom: 20px;
  color: rgba(255, 255, 255, 0.7);
  font-family: 'Roboto', sans-serif;
}

.section-text {
  color: rgba(255, 255, 255, 0.7); 
  font-size: 1.4rem;
  margin-bottom: 20px; 
  font-family: 'Roboto', sans-serif;
}

.about-image {
  width: 100%;
  height: auto;
  border-radius: 10px;
}

.services {
  color: #ccc; 
  font-size: 1rem;
  padding-top: 2rem; 
  margin-bottom: -3rem;
  font-family: 'Roboto', sans-serif;
}

@media screen and (max-width: 768px) {
  .services {
    margin-bottom: 10px; 
  }
}

</style>
