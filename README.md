# vishnu
setting up website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Online Shopping</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">
      <h1>vishnu Clothing</h1>
    </div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#shop">Shop</a></li>
        <li><a href="#cart">Cart (0)</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <div class="hero">
      <h2>Welcome to Vishnu Clothing</h2>
      <p>Your one-stop destination for all things shopping.</p>
    </div>
  </section>

  <section id="shop">
    <h2>Our Products</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200" alt="Product 1">
        <h3>Product 1</h3>
        <p>$19.99</p>
        <button class="add-to-cart">Add to Cart</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200" alt="Product 2">
        <h3>Product 2</h3>
        <p>$29.99</p>
        <button class="add-to-cart">Add to Cart</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200" alt="Product 3">
        <h3>Product 3</h3>
        <p>$39.99</p>
        <button class="add-to-cart">Add to Cart</button>
      </div>
    </div>
  </section>

  <section id="cart">
    <h2>Your Cart</h2>
    <div id="cart-items">
      <p>No items in the cart.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2024 sagar clothing. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
