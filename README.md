<!DOCTYPE html>
<html>
<head>
  <title>Waist Bead Shop</title>
  <style>
    /* CSS for the page layout */
    body {
      margin: 0;
      padding: 0;
      background-color: black;
    }
    /*header */
    header {
      background-color: pink;
      color: white;
      text-align: center;
      padding: 1em;
    }
    /*CSS for main content */
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
    /* CSS for the products section*/
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    /* CSS for individual product*/
    .product {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 1em;
    }
    /* CSS for the footer */
    footer {
      background-color: pink;
      color: black;
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
        <div class="products">
          <div class="product">
            <h3 style="color: strawberry;">Pink Lemonade</h3>
            <button style="background-color: pink;">Buy Now</button>
          </div>
          <div class="product">
            <h3 style="color: red;">Fruit Punch</h3>
            <button style="background-color: pink;">Buy Now</button>
          </div>
          <div class="product">
            <h3 style="color: green;">Grape</h3>
            <button style="background-color: pink;">Buy Now</button>
          </div>
        </div>
    </div>
  </main>

  <footer>
    <p>Copyright ©2022 Waist Bead Shop</p>
  </footer>
</body>
</html>
