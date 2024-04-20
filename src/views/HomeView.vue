<template>
  <section class="hero">
    <div class="container-xl text-center">
      <h1>Welcome to Pizzeria Jupiter</h1>
      <p class="hero-text">Delicious Pizza Made with Love</p>
      <button class="btn btn-primary">View Menu</button>
    </div>
  </section>

  <section class="news">
      <div class="container">
        <div class="row">
          <!-- First News Container -->
          <div class="col-md-4">
            <div class="news-item">
              <img src="/path/to/news1.jpg" alt="News 1" class="news-image">
              <p class="news-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus tempor fringilla massa, in efficitur purus commodo et.</p>
            </div>
          </div>

          <!-- Second News Container -->
          <div class="col-md-4">
            <div class="news-item">
              <img src="/path/to/news2.jpg" alt="News 2" class="news-image">
              <p class="news-text">Sed commodo metus ut magna vehicula, nec pharetra elit consectetur. Nam vel commodo libero.</p>
            </div>
          </div>

          <!-- Third News Container -->
          <div class="col-md-4">
            <div class="news-item">
              <img src="/path/to/news3.jpg" alt="News 3" class="news-image">
              <p class="news-text">Proin vel libero eget odio aliquam convallis. Nam rhoncus massa non augue consequat, ac gravida risus condimentum.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
</template>


<script>
export default {
  
}
</script>

<style>
.hero {
  background-image: url('/src/assets/pizza.jpg'); /* Adjust the path to your image */
  background-size: cover;
  color: #fff;
  padding: 200px 0; /* Increase top and bottom padding for increased height */
}

.container-xl {
  max-width: 1400px;
}

h1 {
  font-size: 3rem;
  text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.7);
}

.hero-text {
  font-size: 1.5rem;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

.news {
  background-color: #f7f7f7;
  padding: 50px 0;
}

.news-item {
  text-align: center;
  margin-bottom: 30px;
}

.news-image {
  width: 100%;
  max-width: 300px;
  height: auto;
  border-radius: 10px;
}

.news-text {
  font-size: 16px;
  margin-top: 15px;
}

</style>
