# SOLEX — Premium Sneaker Store

## Project Overview

SOLEX is a modern, responsive sneaker e-commerce website concept built with HTML, CSS, and JavaScript. It presents premium sneakers in a clean storefront and demonstrates a typical online shopping journey, from browsing products to reviewing a cart and completing a sample checkout flow.

## Features

- **Responsive storefront:** Navigation and layouts designed for desktop and smaller screens.
- **Hero section:** Promotional banner with a featured sneaker and shopping links.
- **Featured products:** Product cards with images, prices, ratings, sale labels, and add-to-cart controls.
- **Product details:** Product gallery, thumbnail images, UK shoe-size selection, and quantity controls.
- **Shopping cart:** Add products, change quantities or sizes, remove items, and view the order summary.
- **Search:** Search interface for finding sneakers in the product listing.
- **Wishlist:** Toggle wishlist controls on product cards and the product detail section.
- **Coupon interface:** Apply a coupon code in the cart or checkout summary when supported by the page logic.
- **Checkout demonstration:** Contact email field and selectable card, UPI, net-banking, and crypto demonstration options.
- **Order confirmation modal:** A sample confirmation flow after checkout validation.
- **Responsive navigation:** Desktop navigation and a mobile menu.
- **Visual styling:** Inter font, Font Awesome icons, rounded cards, subtle shadows, and a lime accent colour.

> **Important:** This is a front-end demonstration project. The checkout does not process real payments, and the interface is not connected to a payment gateway, inventory service, user-account system, or backend order database. Do not enter real payment details.

## Technologies Used

- HTML5 — page structure and content
- CSS3 — layout, styling, responsive design, and visual effects
- JavaScript — interactive shopping and checkout demonstrations
- Google Fonts (Inter) — typography
- Font Awesome 6 — interface icons
- Unsplash image URLs — sneaker imagery

## Project Structure

Keep the HTML and CSS files in the same folder:

```text
SOLEX/
├── index.html
├── style.css
└── README.md
```

If your HTML file has a different name, you can either rename it to `index.html` or use that filename when opening the page. The HTML links to the stylesheet using:

```html
<link rel="stylesheet" href="style.css">
```

Make sure the stylesheet is named exactly `style.css`.

## How to Run the Project

1. Download or copy `index.html` and `style.css` into one folder.
2. Save this README as `README.md` in the same folder.
3. Check that the HTML file links to `style.css`.
4. Open `index.html` in a modern web browser such as Google Chrome, Microsoft Edge, or Firefox.
5. For the complete experience, use an internet connection so externally hosted fonts, icons, and images can load.

No package installation or build step is required for this front-end demo.

## How to Use the Website

1. Browse the featured sneakers in the Shop section.
2. Use the search control to filter the displayed products.
3. Select a product, choose a size, and set the quantity where applicable.
4. Add items to the shopping cart.
5. Review quantities, remove items if needed, and check the order summary.
6. Try the coupon interface if a supported demonstration code is defined in the JavaScript.
7. Continue to checkout, enter an email address, and choose a payment-method demonstration.
8. Submit the checkout form to view the sample order confirmation.

The available interactions depend on the JavaScript included in `index.html`.

## Customization

- **Products:** Edit product names, categories, prices, ratings, and image URLs in `index.html`.
- **Colours:** Change the CSS custom properties near the top of `style.css`, including `--primary`, `--accent`, and `--background`.
- **Typography:** Update the Google Fonts link in the HTML if you want a different font.
- **Images:** Replace the Unsplash URLs with your own properly licensed product images.
- **Content:** Update the hero text, store statistics, product descriptions, and footer details to suit your project.

## Limitations and Future Improvements

This project is intended as a front-end learning/demo website. Possible next steps include:

- Connect a backend and database for products, accounts, and orders.
- Integrate a trusted payment provider in a secure server-side flow.
- Add server-side validation and reliable inventory management.
- Implement persistent cart and wishlist storage if not already included.
- Add product filters, sorting, and a dedicated order-history page.
- Improve accessibility testing and provide local image assets for offline use.

## Credits

- Google Fonts for the Inter typeface
- Font Awesome for icons
- Unsplash for remotely hosted sneaker imagery

## License

This project is provided for learning and demonstration. Check the licences and usage terms for any external images, fonts, or icon resources before using the project commercially.
