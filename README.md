# National Law Books Agency

A small online shop for National Law Books Agency, a law bookstore and publisher serving Jammu and Kashmir. Visitors can browse law books and publications, plus clothing, stickers, and stationery.

## Preview the website

Open `index.html` in a web browser. The site is built with plain HTML, CSS, and JavaScript, so there is no setup or build step.

## Pages

- Home page with featured products and Our Publications
- Shop and product details
- Cart and WhatsApp checkout
- About and Contact pages

## Edit the products

Open `js/products.js` and edit the `window.PRODUCTS` list. Product details and prices live there. Put product images in `images/` and update each product's image path.

## Edit the design and pages

- `css/style.css` controls the site design and mobile layout.
- The `.html` files contain each page's content.
- `js/main.js` controls the menu, search, cart, and WhatsApp order flow.

The cart is saved in the visitor's browser. Checkout prepares an order message for WhatsApp, where orders and payment screenshots are reviewed manually. Replace the QR placeholder on `checkout.html` with the real payment QR before launch.
