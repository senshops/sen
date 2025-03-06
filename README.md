<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Online Shop</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">
            <h1>My Online Shop</h1>
        </div>
        <div class="cart">
            <button id="cart-button">Cart (0)</button>
        </div>
    </header>

    <!-- Product Listing -->
    <section class="products">
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product 1">
            <h3>Product 1</h3>
            <p>$10.00</p>
            <button class="add-to-cart" data-name="Product 1" data-price="10.00">Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product 2">
            <h3>Product 2</h3>
            <p>$20.00</p>
            <button class="add-to-cart" data-name="Product 2" data-price="20.00">Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product 3">
            <h3>Product 3</h3>
            <p>$30.00</p>
            <button class="add-to-cart" data-name="Product 3" data-price="30.00">Add to Cart</button>
        </div>
    </section>

    <!-- Cart Modal -->
    <div id="cart-modal" class="cart-modal">
        <div class="cart-content">
            <h2>Your Cart</h2>
            <ul id="cart-items"></ul>
            <p>Total: $<span id="total-price">0.00</span></p>
            <button id="checkout-button">Proceed to Checkout</button>
            <button id="close-cart">Close</button>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 My Online Shop</p>
    </footer>

    <script src="app.js"></script>
</body>
</html>
