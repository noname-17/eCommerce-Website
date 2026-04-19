# Thapa eCommerce Store

A vanilla JavaScript eCommerce website built with Vite.

## 📁 Project Structure

```
ecom-project/
├── index.html              # Home page
├── about.html              # About page
├── contact.html            # Contact page
├── products.html           # Products listing page
├── addToCart.html          # Cart page
├── main.js                 # Main entry point (loaded by index.html & products.html)
├── vite.config.js          # Vite configuration
├── package.json
├── .gitignore
├── public/
│   └── images/             # Static images (logo, product images, etc.)
└── src/
    ├── style.css           # Global styles
    ├── api/
    │   └── products.json   # Product data
    └── js/
        ├── addToCart.js              # Add product to localStorage cart
        ├── fetchQuantityFromCartLS.js # Get quantity/price from cart LS
        ├── footer.js                 # Dynamic footer injection
        ├── getCartProducts.js        # Read cart from localStorage
        ├── homeProductCards.js       # Render product cards on home/products page
        ├── homeQuantityToggle.js     # +/- quantity toggle on product cards
        ├── incrementDecrement.js     # +/- quantity in cart page
        ├── removeProdFromCart.js     # Remove item from cart
        ├── showAddToCartCards.js     # Render cart page products (entry for addToCart.html)
        ├── showToast.js              # Toast notification utility
        ├── updateCartProductTotal.js # Recalculate cart totals
        └── updateCartValue.js        # Update cart count in navbar
```

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## ⚠️ Images

Place your images inside the `public/images/` folder. They are referenced in `products.json` as `../images/<name>.png`. Vite serves the `public/` folder at the root, so in production they'll be at `/images/<name>.png`.

Update `products.json` image paths to `/images/<name>.png` if needed after moving images in.
