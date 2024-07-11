<template>
  <footer class="footer bg-dark text-white">
    <div class="container py-3">
      <p class="mb-4">We accept payment in Euros or below mentioned cards</p>
      <!-- Payment Cards Icons -->
      <div class="payment-cards mb-4">
        <img src="../assets/diners.png" alt="Card 1" class="payment-card">
        
      </div>&nbsp;

      <div class="row"> 
        <!-- Contact Information -->
        <div class="col-md-4 mb-4 mb-md-0">
          <h5>Contact Us</h5>
          <p class="footp">Email: pizzeriajupiter@net.hr</p>
          <p class="footp">Phone: 052 214 333</p>
          <p class="footp">Address: Castropola 42, Pula, Croatia, 52100</p>
        </div>
        
        <!-- Social Media Links -->
        <div class="col-md-4 mb-4 mb-md-0">
          <h5>Follow Us</h5>
          <ul class="list-unstyled">
            <li><a href="https://www.facebook.com/profile.php?id=100063616896504">Facebook</a></li>
            <li><a href="https://www.instagram.com/jupiterpizzeria/?hl=en">Instagram</a></li>
          </ul>
        </div>
        
        <!-- Copyright Notice -->
        <div class="col-md-4">
          <h5>&copy; 2024 Mateo Rumac</h5>
          <p class="footp">All rights reserved.</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');

.footer {
  padding: 20px 0;
}

.footer h5 {
  color: #fff;
  font-weight: bold;
  margin-bottom: 20px;
  font-family: 'Roboto', sans-serif;
}

.footp {
  font-family: 'Roboto', sans-serif;
}

.footer p {
  color: #ccc;
  margin-bottom: 10px;
  font-family: 'Roboto', sans-serif;
}

.footer ul {
  list-style: none;
  padding: 0;
}

.footer ul li {
  margin-bottom: 10px;
}

.footer ul li a {
  color: #ccc;
  text-decoration: none;
  font-family: 'Roboto', sans-serif;
}

.footer ul li a:hover {
  color: #fff;
}

.payment-cards img {
  width: 300px;
  height: auto;
  margin-right: 10px;
}

.footer .container {
  padding-left: 0;
  padding-right: 0;
}
</style>
