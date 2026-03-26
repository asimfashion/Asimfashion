<!DOCTYPE html>
<html>
<head>
    <title>Asim Fashion</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f5f5;
        }

        .header {
            background: black;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 30px;
            font-weight: bold;
            letter-spacing: 2px;
        }

        .tagline {
            text-align: center;
            padding: 10px;
            color: gray;
        }

        .categories {
            text-align: center;
            margin: 20px;
        }

        .categories button {
            margin: 10px;
            padding: 12px 20px;
            border: none;
            background: black;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }

        .categories button:hover {
            background: #444;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            padding: 20px;
        }

        .card {
            background: white;
            padding: 10px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .card img {
            width: 100%;
            border-radius: 10px;
        }

        .whatsapp {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: green;
            color: white;
            padding: 15px;
            border-radius: 50%;
            font-size: 20px;
            text-decoration: none;
        }
    </style>
</head>

<body>

<div class="header">ASIM FASHION</div>
<div class="tagline">Premium Casual & Linen Wear</div>

<div class="categories">
    <button>Shirts</button>
    <button>Kurtas</button>
    <button>Lowers</button>
    <button>Shoes</button>
</div>

<div class="products">

    <div class="card">
        <img src="https://via.placeholder.com/200" />
        <p>Stylish Shirt</p>
    </div>

    <div class="card">
        <img src="https://via.placeholder.com/200" />
        <p>Kurta Collection</p>
    </div>

    <div class="card">
        <img src="https://via.placeholder.com/200" />
        <p>Comfort Lower</p>
    </div>

    <div class="card">
        <img src="https://via.placeholder.com/200" />
        <p>Trendy Shoes</p>
    </div>

</div>

<a class="whatsapp" href="https://wa.me/91XXXXXXXXXX">💬</a>

</body>
</html>
