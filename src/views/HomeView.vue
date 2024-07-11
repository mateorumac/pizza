<template>
  <section class="hero">
    <div class="container-xl text-center">
      <h1>Welcome to Pizzeria Jupiter</h1>
      <p class="hero-text">Delicious Pizza Made with Love</p>
      <router-link to="/menu">
        <button class="btn-primary"><b>View Menu</b></button>
      </router-link>
    </div>
  </section>

  <section class="news">
      <div class="container">
        <!-- Title -->
        <h2 class="news-title text-center mb-4" style="margin-top: -50px;">Latest News </h2> &nbsp;

        <div class="row">
          <!-- First News Container -->
          <div class="col-md-4">
            <div class="news-item">
              <img src="../assets/news1.jpg" alt="News 1" class="news-image">
              <p class="news-text">EVERY WEDNESDAY we have 2️⃣0️⃣% DISCOUNT on all PIZZAS</p>
            </div>
          </div>

          <!-- Second News Container -->
          <div class="col-md-4">
            <div class="news-item">
              <img src="../assets/news2.jpg" alt="News 2" class="news-image">
              <p class="news-text">Which do you choose, a regular burger or a burger stuffed with cheese?</p>
            </div>
          </div>

          <!-- Third News Container -->
          <div class="col-md-4">
            <div class="news-item">
              <img src="../assets/news3.jpg" alt="News 3" class="news-image">
              <p class="news-text">One of the favorites - Istrian steak with white mushroom sauce</p>
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
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');

body {
  overflow-x: hidden;
}

.hero {
  background-image: url('/src/assets/pizza.jpg'); 
  background-size: cover;
  color: #fff;
  padding: 200px 0; 
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
  font-family: 'Roboto', sans-serif; 

}

.news {
  background-color: #343a40;
  color: #fff; 
  padding: 100px 0; 
}

.news-title {
  font-size: 2.5rem; 
  font-family: 'Roboto', sans-serif; 

}

.news-image {
  width: 100%;
  transition: transform 0.3s ease-in-out;
  height: 200px;
  object-fit: cover;
  border-radius: 10px;
}

.news-image:hover {
  transform: scale(1.1); 
}

.news-text {
  font-size: 16px;
  margin-top: 15px;
  font-family: 'Roboto', sans-serif; 

}

.btn-primary {
  background-color: #fddb3a; 
  color: #343a40; 
  border: none;
  padding: 12px 24px;
  font-size: 1.1rem;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.btn-primary:hover {
  background-color: #ffbf00; 
}
</style>
