# Task 11: CSS Mini Project - Thala 7 Sneaker Store

A four-page sneaker store built with plain HTML and CSS only (no Bootstrap, no JavaScript). Layouts use Flexbox.

## Files

- `index.html` - 1. Landing page (header, hero section, service overview)
- `product.html` - 2. Product display page (main display + scrolling gallery)
- `cart.html` - 3. Shopping cart page (cart table, order summary, continue shopping link)
- `payment.html` - 4. Payment page (checkout form and order summary)
- `style.css` - one stylesheet linked from all four pages
- `images/` - sneaker images (`shoe-1.png` to `shoe-5.png`) and `avatar.png`
- `Readme.md` - this file

## What was built

### 1. Landing page
- **Header (Flexbox):** logo on the left, menus in the centre, search box, cart icon and profile picture on the right.
- **Hero section:** two divs. Left: heading, description and "Shop Now" button. Right: sneaker image.
- **Service overview:** a full-width orange section outside the main hero div showing 2k+ Reviews, 30k+ Customers, High Quality and 4.5/5 Rating.

### 2. Product display page
- Same header as the landing page.
- **Main display:** product image on the left; name, description, price, sale details, quantity and "Add to Cart" button on the right.
- **Bottom gallery:** all sneaker images in a horizontally scrolling Flex container.

### 3. Shopping cart page
- Same header as the landing page.
- **Left container:** "Shopping Cart" heading and a table with Product, Quantity and Price, plus a remove icon on each row.
- **Right container:** card with coupon input and "Apply Coupon" button, Sub Total, Taxes, Discount and Total, a "Pay Now" button and security badges.
- **Bottom container:** "Continue Shopping" link at the bottom left.

### 4. Payment page
- **Left container:** "Checkout" sub-heading, Email ID field, and a payment card with method options (Card, Crypto, Bank, more), Card Number, Expiry, CVC, Country and ZIP. The payment method boxes are pure CSS radio buttons.
- **Right container:** "Order Summary" heading, coupon card with the totals, "Pay Now" button and security badges.

## Notes

- This is a demo store: the forms do not send or store any data and the coupon / Pay Now buttons do not process anything.
- The sneaker pictures and avatar are illustrations drawn for this project. Replace the files in `images/` (same names) to use your own photos.
- Every price on the product, cart and payment pages is consistent: 3 x Rs.1,334 = Rs.4,002 (taxes included in the price).

## How to run

Keep all files and the `images` folder together and open `index.html` in a browser. Use the header links, "Add to Cart", "Pay Now" and "Continue Shopping" to move between pages.
