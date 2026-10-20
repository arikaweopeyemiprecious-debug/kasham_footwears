KASHAM FOOTWEARS — WEBSITE HANDOVER
===================================

FILES
- index.html: Home page
- shop.html: All products, category filter, search and sorting
- product.html: Product details page (loaded by product ID)
- cart.html: Cart, quantity controls and WhatsApp checkout
- about.html: About the brand
- contact.html: Contact form that opens WhatsApp
- assets/products.js: All 30 product records, categories, prices and online image URLs
- assets/style.css: Complete desktop/mobile responsive styling and hamburger menu
- assets/app.js: Product rendering, cart, search, filters and WhatsApp actions
- manifest.json and service-worker.js: Installable PWA support when hosted over HTTPS or localhost

IMPORTANT BEFORE GOING LIVE
1. Open assets/app.js and replace BOTH occurrences of 2348000000000 with the client's WhatsApp number in international format without +, spaces or leading 0. Example format: 2348012345678.
2. Open assets/products.js and replace product names and image URLs with the client's exact products/photos as needed. Images currently use public online Unsplash URLs; this project does not download the photos into the folder.
3. Confirm product prices, sizes, stock, delivery fees and return policy with the client before taking orders.
4. Test WhatsApp checkout on a phone after replacing the number.
5. For the install prompt/PWA service worker to work, host the site on HTTPS (for example, a proper static host) or run it on localhost. Opening HTML directly from a file manager does not enable all PWA features.
6. This is a front-end-only site: the cart is saved in the customer's browser using localStorage. It does not have a server database, admin dashboard, payment gateway, stock management or automated order records.

PRODUCT CATEGORIES AND PRICES
Half Shoes — ₦35,000
Shoes — ₦45,000
Slides for Female — ₦25,000
Slides for Male — ₦25,000
Flats for Female — ₦15,000
Flats for Male — ₦15,000
Platform for Female — ₦20,000
Platform for Male — ₦20,000
Platform Sandals for Female — ₦20,000
Platform Sandals for Male — ₦20,000
Flat Sandals for Female — ₦15,000
Flat Sandals for Male — ₦15,000

To preview, open index.html in a browser. For best testing, use VS Code Live Server or another local HTTP server.
