<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gadget Hub</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f7f7f7;
    }
    header {
      background: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 20px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .product {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      width: 100%;
      max-height: 150px;
      object-fit: contain;
    }
    .contact {
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      max-width: 600px;
      margin: 0 auto;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 10px;
    }
    a.button {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background: #007bff;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Gadget Hub</h1>
    <p>Your one-stop shop for the latest tech</p>
  </header>  <section>
    <h2>Featured Products</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x150" alt="Smartwatch">
        <h3>Smartwatch</h3>
        <p>$49.99</p>
        <a href="#contact" class="button">Order Now</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x150" alt="Bluetooth Speaker">
        <h3>Bluetooth Speaker</h3>
        <p>$39.99</p>
        <a href="#contact" class="button">Order Now</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x150" alt="Phone Stand">
        <h3>Phone Stand</h3>
        <p>$19.99</p>
        <a href="#contact" class="button">Order Now</a>
      </div>
    </div>
  </section>  <section id="contact">
    <h2>Contact & Orders</h2>
    <div class="contact">
      <p>📱 <strong>WhatsApp:</strong> <a href="https://wa.me/your-number">Chat with us</a></p>
      <p>📧 <strong>Email:</strong> gadgethub@example.com</p>
      <form>
        <p><label>Name:<br><input type="text" name="name" required></label></p>
        <p><label>Email:<br><input type="email" name="email" required></label></p>
        <p><label>Message:<br><textarea name="message" rows="4" required></textarea></label></p>
        <p><button type="submit">Send</button></p>
      </form>
    </div>
  </section>  <footer>
    &copy; 2025 Gadget Hub. All rights reserved.
  </footer>
</body>
</html># Gadget-Hub-
