# Jisr_store-
Just store جسر يوصل بين البائع والمشتري 
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>جسر ستور</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 0;
      padding: 20px;
    }

    header {
      text-align: center;
      margin-bottom: 30px;
    }

    header img {
      width: 150px;
      margin-bottom: 10px;
    }

    h1 {
      color: #1a237e; /* أزرق غامق */
      margin: 0;
    }

    p.slogan {
      color: #ff9800; /* برتقالي */
      font-weight: bold;
      margin-top: 5px;
    }

    .product {
      background-color: #fff;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      text-align: center;
      max-width: 400px;
    }

    .product img {
      width: 100%;
      border-radius: 10px;
    }

    .price {
      font-size: 24px;
      color: #ff5722;
      margin: 10px 0;
    }

    .order-button {
      background-color: #1a237e;
      color: #fff;
      padding: 12px 20px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
    }

    .order-button:hover {
      background-color: #3949ab;
    }

  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="لوغو جسر ستور">
    <h1>جسر ستور</h1>
    <p class="slogan">جسر يوصل بين البائع والمشتري</p>
  </header>

  <div class="product">
    <img src="product.jpg" alt="صورة المنتج">
    <p class="price">السعر: 3990 دج</p>
    <button class="order-button" onclick="window.location.href='https://forms.gle/PUT_YOUR_FORM_LINK_HERE'">اطلب الآن</button>
  </div>

</body>
</html>
