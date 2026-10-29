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

Open `js/products.js` and edit the `window.PRODUCTS` list. Product details, prices, ISBNs, editions, and subject sections live there. The supplied catalogue contributed 813 book listings; all imported book entries use the shared `images/catalogue-book-placeholder.svg` image. Replace that file with a real book image later, or change individual image paths if you add category-specific placeholders.

The catalogue PDF filename says October 2027, while its cover says October 2026. Its listed prices are subject to change, so confirm price and availability before accepting an order. The Shop page shows 24 products at a time and includes a catalogue price note.

## Edit the design and pages

- `css/style.css` controls the site design and mobile layout.
- The `.html` files contain each page's content.
- `js/main.js` controls the menu, search, cart, and WhatsApp order flow.

The cart is saved in the visitor's browser. Checkout prepares an order message for WhatsApp, where orders and payment screenshots are reviewed manually. Replace the QR placeholder on `checkout.html` with the real payment QR before launch.
