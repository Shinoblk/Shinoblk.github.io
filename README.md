<html>
<head>
  <title>Waist Bead Shop</title>
  <style>
    /* CSS for the page layout */
    body {
      margin: 0;
      padding: 0;
      background-color: pink;
    }

    header {
      background-color: pink;
      color: Red;
      text-align: center;
      padding: 1em;
    }

    main {
      margin: 0;
      padding: 0;
    }

    /* CSS for the main content area */
    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
    }

    /* CSS for the product section */
    .product-section {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    /* CSS for the product options */
    .product-option {
      background-color: #ffc0cb;
      padding: 1em;
      margin: 1em;
      text-align: center;
    }

    /* CSS for the product option: Pink Lemonade */
    .product-option-pink-lemonade {
      color: strawberry;
    }

    /* CSS for the product option: Grape */
    .product-option-grape {
      color: green;
    }

    /* CSS for the product option: Fruit Punch */
    .product-option-fruit-punch {
      color: red;
    }

    /* CSS for the footer */
    footer {
      background-color: #4CAF50;
      color: Black;
      text-align: center;
      padding: 1em;
      position: absolute;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to my waist bead shop!</h1>
  </header>

  <main>
    <div class="container">
      <div class="product-section">
        <div class="product-option product-option-pink-lemonade">
          <h2>Pink Lemonade</h2>
          <p>Buy now</p>
        </div>
        <div class="product-option product-option-grape">
          <h2>Grape</h2>
          <p>Buy now</p>
        </div>
        <div class="product-option product-option-fruit-punch">
          <h2>Fruit Punch</h2>
          <p>Buy now</p>
        </div>
      </div>
    </div>
  </main>

  <footer>
    <p>Copyright ©2022 My Website</p>
  </footer>
</body>
</html>
