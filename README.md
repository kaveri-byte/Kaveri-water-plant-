# Kaveri-water-plant-
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kaveri Water Plant</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f0f8ff;
    }
    header {
      background-color: #00aaff;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #0077aa;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    section {
      padding: 30px;
      background: white;
      margin: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    form {
      display: flex;
      flex-direction: column;
    }
    input, select, textarea {
      margin: 10px 0;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 16px;
    }
    .submit-button {
      background-color: #28a745;
      color: white;
      padding: 15px;
      font-size: 18px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background: #0077aa;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body><header>
  <h1>Kaveri Water Plant</h1>
  <p>Providing Cool Water and Mineral Water</p>
</header><nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#services">Services</a>
  <a href="#products">Products</a>
  <a href="#order">Order</a>
  <a href="#contact">Contact</a>
</nav><section id="home">
  <h2>Welcome</h2>
  <p>Welcome to Kaveri Water Plant — your trusted source for cool water and pure mineral water. Fresh, clean, and ready to deliver to your home!</p>
</section><section id="about">
  <h2>About Us</h2>
  <p>Started in 2023, Kaveri Water Plant was founded with one goal: To provide pure drinking water directly to homes. Customers can easily book online, choosing between cool water and normal mineral water, and we deliver it quickly!</p>
</section><section id="services">
  <h2>Services</h2>
  <ul>
    <li>Supply of cool water cans</li>
    <li>Supply of mineral water cans</li>
    <li>Quick and safe home delivery</li>
    <li>Easy online booking</li>
  </ul>
</section><section id="products">
  <h2>Products</h2>
  <ul>
    <li>14 Liter Cool Water Cans</li>
    <li>14 Liter Mineral Water Cans</li>
  </ul>
</section><section id="order">
  <h2>Place Your Order</h2>
  <form action="https://formspree.io/f/mnqepyak" method="POST">
    <input type="text" name="Name" placeholder="Your Name" required>
    <input type="tel" name="Phone" placeholder="Your Phone Number" required>
    <textarea name="Address" placeholder="Your Address" required></textarea>
    <select name="Water Type" required>
      <option value="">Select Water Type</option>
      <option value="Cool Water">Cool Water</option>
      <option value="Mineral Water">Mineral Water</option>
    </select>
    <input type="number" name="Number of Cans" placeholder="Number of Cans" required>
    <button type="submit" class="submit-button">Submit Order</button>
  </form>
</section><section id="contact">
  <h2>Contact Us</h2>
  <p>Phone: <a href="tel:9640007771">9640007771</a></p>
  <p>Email: <a href="mailto:kaveriwater91@gmail.com">kaveriwater91@gmail.com</a></p>
</section><footer>
  &copy; 2025 Kaveri Water Plant. All rights reserved.
</footer></body>
</html>
