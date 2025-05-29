# tsekouu-site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Tsek Store - Tsekoubuds Wireless Earbuds</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
      background: #f9f9f9;
      color: #222;
    }
    header {
      text-align: center;
      margin-bottom: 40px;
    }
    header h1 {
      font-size: 3em;
      color: #0070ba;
      margin-bottom: 0;
    }
    header h2 {
      margin-top: 0;
      font-weight: normal;
      color: #555;
    }
    .product-image {
      width: 100%;
      max-width: 480px;
      display: block;
      margin: 0 auto 20px;
      border-radius: 15px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.15);
    }
    .product-info {
      background: white;
      border-radius: 15px;
      padding: 20px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      margin-bottom: 40px;
    }
    .product-info p {
      line-height: 1.5;
      font-size: 1.1em;
    }
    ul.features {
      list-style: disc inside;
      margin: 15px 0;
      padding-left: 0;
    }
    ul.features li {
      margin-bottom: 8px;
      font-size: 1em;
    }
    .price {
      font-size: 2em;
      font-weight: bold;
      color: #0070ba;
      margin: 20px 0;
      text-align: center;
    }
    .paypal-button {
      display: block;
      margin: 0 auto 40px;
      text-align: center;
    }
    form.order-form {
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      max-width: 500px;
      margin: 0 auto 60px;
    }
    form.order-form h3 {
      margin-bottom: 20px;
      color: #0070ba;
      text-align: center;
    }
    form.order-form label {
      display: block;
      margin-bottom: 6px;
      font-weight: bold;
      color: #333;
    }
    form.order-form input,
    form.order-form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 1em;
      box-sizing: border-box;
      resize: vertical;
    }
    form.order-form button {
      background-color: #0070ba;
      color: white;
      padding: 12px 20px;
      font-size: 1.1em;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      width: 100%;
      transition: background-color 0.3s ease;
    }
    form.order-form button:hover {
      background-color: #005c99;
    }
    .reviews {
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      max-width: 600px;
      margin: 0 auto 60px;
    }
    .reviews h3 {
      color: #0070ba;
      margin-bottom: 20px;
      text-align: center;
    }
    .review {
      border-bottom: 1px solid #ddd;
      padding: 10px 0;
    }
    .review:last-child {
      border-bottom: none;
    }
    .review strong {
      display: block;
      margin-bottom: 6px;
      color: #333;
    }
    footer {
      text-align: center;
      font-size: 0.9em;
      color: #666;
      margin-bottom: 40px;
    }
    .drop-ship-note {
      max-width: 600px;
      background: #e0f0ff;
      border-left: 5px solid #0070ba;
      margin: 40px auto;
      padding: 20px;
      border-radius: 10px;
      font-size: 1em;
      color: #004080;
      line-height: 1.4;
    }
  </style>
</head>
<body>

  <header>
    <h1>Tsek Store</h1>
    <h2>Tsekoubuds Wireless Earbuds</h2>
  </header>

  <img
    src="https://ae01.alicdn.com/kf/Sb71b02eb9b7f48c09162ce9b2c5d8c48O/Waterproof-Bluetooth-Headphones-Stereo-Earbuds-Wireless-Earphone-Headset-With-Mic-For-Sports-TWS-Earphones.jpg"
    alt="Tsekoubuds Wireless Earbuds"
    class="product-image"
  />

  <section class="product-info">
    <p>Experience wireless freedom with high-quality sound and all-day comfort. Perfect for active lifestyles!</p>
    <p>The Tsekoubuds Wireless Earbuds offer premium features including advanced Bluetooth 5.0 connectivity, stereo sound, waterproof design, and ergonomic fit. Ideal for workouts, commuting, and daily use.</p>

    <ul class="features">
      <li>Bluetooth 5.0 for stable connection</li>
      <li>Stereo sound with deep bass</li>
      <li>IPX7 Waterproof rating</li>
      <li>Long battery life with charging case</li>
      <li>Built-in microphone for calls</li>
      <li>Touch controls for easy operation</li>
    </ul>

    <p class="price">$50.00</p>

    <div class="paypal-button">
      <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
        <input type="hidden" name="cmd" value="_xclick" />
        <input type="hidden" name="business" value="alexandrosalexandriou@gmail.com" />
        <input type="hidden" name="item_name" value="Tsekoubuds Wireless Earbuds" />
        <input type="hidden" name="amount" value="50.00" />
        <input type="hidden" name="currency_code" value="USD" />
        <input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_buynow_LG.gif" border="0" name="submit" alt="Buy Now with PayPal" />
        <img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1" />
      </form>
    </div>
  </section>

  <form class="order-form" onsubmit="sendOrder(event)">
    <h3>Order Form</h3>
    <label for="name">Full Name</label>
    <input id="name" name="name" type="text" required placeholder="Your full name" />

    <label for="email">Email Address</label>
    <input id="email" name="email" type="email" required placeholder="Your email address" />

    <label for="address">Shipping Address</label>
    <textarea id="address" name="address" rows="3" required placeholder="Your shipping address"></textarea>

    <button type="submit">Send Order Info</button>
  </form>

  <section class="reviews">
    <h3>Customer Reviews</h3>
    <div class="review">
      <strong>⭐️⭐️⭐️⭐️⭐️ - Amazing Sound Quality!</strong>
      <p>These earbuds exceeded my expectations. The bass is deep, and they stay in my ears during workouts!</p>
    </div>
    <div class="review">
      <strong>⭐️⭐️⭐️⭐️ - Great Value</strong>
      <p>Battery life is fantastic, and they’re super comfortable. Highly recommend for the price.</p>
    </div>
    <div class="review">
      <strong>⭐️⭐️⭐️⭐️⭐️ - Perfect for My Commute</strong>
      <p>Noise isolation is excellent and call quality is crystal clear. Will buy again for gifts.</p>
    </div>
  </section>

  <section class="drop-ship-note">
    <h3>How It Works</h3>
    <p>Once your payment is completed via PayPal, you’ll receive an email confirmation with order details. We then manually place your order on AliExpress and ship directly to you. Please allow extra time for international shipping.</p>
  </section>

  <footer>
    &copy; 2025 Tsek Store
  </footer>

  <script>
    function sendOrder(event) {
      event.preventDefault();
      const name = event.target.name.value.trim();
      const email = event.target.email.value.trim();
      const address = event.target.address.value.trim();

      if (!name || !email || !address) {
        alert('Please fill out all fields.');
        return;
      }

      // Compose email to seller with order info
      const subject = encodeURIComponent('New Order - Tsekoubuds Wireless Earbuds');
      const body = encodeURIComponent(
        `Name: ${name}\nEmail: ${email}\nAddress:\n${address}`
      );

      // Open mail client to send order info
      window.location.href = `mailto:alexandrosalexandriou@gmail.com?subject=${subject}&body=${body}`;

      alert('Thank you for your order! Please complete the PayPal payment.');
      event.target.reset();
    }
  </script>
</body>
</html>
