<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Asim Fashion</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    /* Logo */
    .logo {
      text-align: center;
      font-size: 40px;
      font-weight: bold;
      padding: 20px;
    }

    /* Categories */
    .categories {
      text-align: center;
      margin: 20px 0;
    }

    .categories button {
      margin: 5px;
      padding: 10px 15px;
      border: none;
      background: black;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }

    /* Product Section */
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
      padding: 20px;
    }

    .product {
      border: 1px solid #ddd;
      padding: 10px;
      text-align: center;
      border-radius: 10px;
    }

    .product img {
      width: 100%;
      border-radius: 10px;
    }

    /* WhatsApp Button */
    .whatsapp-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      font-size: 24px;
      padding: 12px 15px;
      border-radius: 50%;
      text-decoration: none;
    }
  </style>
</head>

<body>

  <!-- Logo -->
  <h1 class="logo">Asim Fashion</h1>

  <!-- Categories -->
  <div class="categories">
    <button>Kurta</button>
    <button>Shirt</button>
    <button>Shoes</button>
  </div>

  <!-- Products -->
  <div class="products">
    <div class="product">
      <img src="https://via.placeholder.com/150" alt="">
      <p>Kurta</p>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/150" alt="">
      <p>Shirt</p>
    </div>

    <div class="product">
      <img src="https://via.placeholder.com/150" alt="">
      <p>Shoes</p>
    </div>
  </div>

  <!-- WhatsApp Button -->
  <a href="https://wa.me/91XXXXXXXXXX" target="_blank" class="whatsapp-btn">
    💬
  </a>

</body>
</html>
