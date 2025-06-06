<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yay! It's BOGO</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="bogo-container">
        <h2>YAY! IT'S BOGO</h2>
        <div class="bogo-options">
            <label class="bogo-option">
                <input type="radio" name="bogo" value="1-unit" onclick="updateTotal(10)">
                <span>1 Unit</span>
                <span class="discount">10% OFF</span>
                <span class="price">$10.00 USD</span>
            </label>
            <label class="bogo-option selected">
                <input type="radio" name="bogo" value="2-unit" checked onclick="updateTotal(18)">
                <span>2 Unit</span>
                <span class="discount">20% OFF</span>
                <span class="price">$18.00 USD</span>
                <span class="popular">MOST POPULAR</span>
            </label>
            <div class="selectors">
                <div class="selector-group">
                    <span>#1</span>
                    <select class="size">
                        <option value="S">S</option>
                        <option value="M">M</option>
                        <option value="L">L</option>
                    </select>
                    <select class="color">
                        <option value="Black">Black</option>
                        <option value="Red">Red</option>
                        <option value="Blue">Blue</option>
                    </select>
                </div>
                <div class="selector-group">
                    <span>#2</span>
                    <select class="size">
                        <option value="S">S</option>
                        <option value="M">M</option>
                        <option value="L">L</option>
                    </select>
                    <select class="color">
                        <option value="">Colour</option>
                        <option value="Black">Black</option>
                        <option value="Red">Red</option>
                        <option value="Blue">Blue</option>
                    </select>
                </div>
            </div>
            <label class="bogo-option">
                <input type="radio" name="bogo" value="3-unit" onclick="updateTotal(24)">
                <span>3 Unit</span>
                <span class="discount">30% OFF</span>
                <span class="price">$24.00 USD</span>
            </label>
        </div>
        <div class="shipping">Free Delivery</div>
        <div class="total">TOTAL: <span id="total-price">$18.00 USD</span></div>
        <button class="add-to-cart">+ Add to Cart</button>
        <div class="powered-by">© Powered by Pumper</div>
    </div>
    <script src="script.js"></script>
</body>
</html>
