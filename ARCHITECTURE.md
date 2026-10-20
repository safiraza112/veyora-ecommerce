# Veyora - Architecture

## 1. Pages (10)
| Page | Purpose |
|---|---|
| index.html | Home: hero, categories, featured products, offer, newsletter |
| shop.html | All products grid |
| categories.html | Women, Men, Accessories, Footwear |
| product.html | Product details, size and colour options, related products |
| cart.html | Sample cart and order summary |
| checkout.html | Shipping form and payment method |
| about.html | About the brand |
| contact.html | Contact form, address, map placeholder |
| login.html | Login and register forms |
| faq.html | Questions in a CSS-only accordion |

## 2. Navigation
- Every page uses the same header and footer, so links are identical everywhere.
- All links are relative (for example `shop.html`), so the site works on GitHub Pages.
- The current page is highlighted with `aria-current="page"` and styled in CSS.
- On mobile, a hamburger menu works with a hidden checkbox and the `:checked` selector, with no JavaScript.
- Flow: Home > Shop > Product > Cart > Checkout.

## 3. How CSS was used
- One stylesheet, `css/style.css`, split into commented sections.
- CSS variables (`:root`) hold colours, fonts and radius.
- Flexbox for the navbar and rows, CSS Grid for product, category and page layouts.
- Hover and focus transitions on buttons, cards and links.
- Responsive design with media queries at 900px and 560px.
- CSS-only components: hamburger menu (checkbox), FAQ accordion (`<details>`), size and colour pickers (radio buttons).
