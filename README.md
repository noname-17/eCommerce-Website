<div align="center">

# QuickTech Store

### A modern eCommerce web app built with Vanilla JavaScript & Vite

[![Live Demo](https://img.shields.io/badge/Live_Demo-quicktechstore.netlify.app-brightgreen?style=for-the-badge)](https://quicktechstore.netlify.app/)
[![Built With](https://img.shields.io/badge/Built_With-Vanilla_JS-yellow?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bundler](https://img.shields.io/badge/Bundler-Vite-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev/)
[![Deploy](https://img.shields.io/badge/Deploy-Netlify-00C7B7?style=for-the-badge&logo=netlify)](https://netlify.com/)

</div>

---

## Screenshots

| Hero Section | Product Listings |
|:---:|:---:|
| ![Hero Section](./scr-github/hero-section.png) | ![Products](./scr-github/products-1.png) |

| Offers & Deals | Cart Page |
|:---:|:---:|
| ![Offers](./scr-github/offers.png) | ![Cart](./scr-github/cart.png) |

> Live Preview: [quicktechstore.netlify.app](https://quicktechstore.netlify.app/)

---

## Features

- **Add to Cart** — persistent cart using localStorage
- **Quantity Controls** — inline increment/decrement on product cards and cart page
- **Remove Items** — delete individual products from cart
- **Live Cart Totals** — prices and counts update in real time
- **Toast Notifications** — feedback on add/remove actions
- **Responsive Design** — mobile-friendly layout
- **Vite Bundler** — fast dev server and optimized production builds

---

## Project Structure

    ecom-project/
    ├── index.html              # Home page
    ├── about.html              # About page
    ├── contact.html            # Contact page
    ├── products.html           # Products listing page
    ├── addToCart.html          # Cart page
    ├── main.js                 # Entry point
    ├── vite.config.js          # Vite configuration
    ├── package.json
    ├── public/
    │   └── images/             # Static assets
    └── src/
        ├── style.css
        ├── api/
        │   └── products.json
        └── js/
            ├── addToCart.js
            ├── fetchQuantityFromCartLS.js
            ├── footer.js
            ├── getCartProducts.js
            ├── homeProductCards.js
            ├── homeQuantityToggle.js
            ├── incrementDecrement.js
            ├── removeProdFromCart.js
            ├── showAddToCartCards.js
            ├── showToast.js
            ├── updateCartProductTotal.js
            └── updateCartValue.js

---

## Getting Started

**Prerequisites:** Node.js v16+ and npm

**Installation:**

    git clone https://github.com/your-username/ecom-project.git
    cd ecom-project
    npm install
    npm run dev

| Command | Description |
|---|---|
| `npm run dev` | Start local dev server at localhost:5173 |
| `npm run build` | Build optimised production bundle to dist/ |
| `npm run preview` | Preview the production build locally |

---

## Images Setup

Place all product images inside the `public/images/` folder. Reference them in `products.json` as `/images/product-name.png`.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 | Structure & styling |
| Vanilla JavaScript ES6+ | All interactivity & logic |
| Vite | Dev server & bundler |
| localStorage | Cart persistence |
| Netlify | Deployment |

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
Designed & Built with love by <b>Rupesh</b>
