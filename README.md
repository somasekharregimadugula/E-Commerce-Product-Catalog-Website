# 🛍️ E-Commerce Product Catalog Website

A responsive, dynamic front-end e-commerce application built with **HTML5, CSS3, and Vanilla JavaScript**. This project simulates a real-world shopping experience by fetching product data dynamically from a JSON file and managing a shopping cart state without a backend database.


## 🌟 Key Features

* Dynamic Product Rendering: Fetches product data asynchronously from `ProductsData.json` to generate product cards at runtime.
* Category Filtering: Filters products (Electronics, Fashion, Furniture, etc.) using URL query parameters to display relevant items without reloading the page.
* Shopping Cart System:
    * Add items to the cart with quantity management.
    * Persists state across navigation.
    * Dynamic total price calculation.
* Custom Notifications: Built-in `notification.js` system to provide real-time feedback (e.g., "Item added to cart") via toast messages.
* Responsive Design: Fully optimized layout for mobile, tablet, and desktop screens using CSS Flexbox and Grid.
* Carousel/Hero Banner: Auto-sliding hero banner on the homepage for feature highlights.

## 🛠️ Tech Stack

* Frontend: HTML5, CSS3, JavaScript (ES6+)
* Data: JSON (Local structured data)
* Versioning: Git, GitHub
* Tools: VS Code

## 📂 Project Structure

```bash
E-Commerce-Product-Catalog-Website/
├── assets/              # Images and icons
├── cart/                # Cart page logic and HTML
├── checkout/            # Checkout page logic and HTML
├── ProductsData.json    # Local database of products
├── index.html           # Main homepage
├── script.js            # Main application logic (Fetching & Rendering)
├── notification.js      # Custom toast notification logic
├── style.css            # Global styles and responsive design
└── README.md            # Project documentation
