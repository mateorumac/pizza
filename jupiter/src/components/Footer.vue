<template>
  <footer class="footer bg-dark text-white">
    <div class="container py-5">
      <div class="row">
        <!-- Contact Information -->
        <div class="col-md-4 mb-4 mb-md-0">
          <h5>Contact Us</h5>
          <p>Email: info@pizzarestaurant.com</p>
          <p>Phone: +1 123-456-7890</p>
          <p>Address: 123 Main St, City, Country</p>
        </div>
        
        <!-- Social Media Links -->
        <div class="col-md-4 mb-4 mb-md-0">
          <h5>Follow Us</h5>
          <ul class="list-unstyled">
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">Instagram</a></li>
            <li><a href="#">LinkedIn</a></li>
          </ul>
        </div>
        
        <!-- Copyright Notice -->
        <div class="col-md-4">
          <h5>&copy; 2024 Pizza Restaurant</h5>
          <p>All rights reserved.</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  padding: 50px 0;
}

.footer h5 {
  color: #fff;
  font-weight: bold;
  margin-bottom: 20px;
}

.footer p {
  color: #ccc;
  margin-bottom: 10px;
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
}

.footer ul li a:hover {
  color: #fff;
}
</style>
