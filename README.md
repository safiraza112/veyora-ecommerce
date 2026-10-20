# Veyora - Fashion E-commerce Website | Web Engineering Assignment 1

A modern, responsive fashion store website built using **pure HTML5 and CSS3 only** (Zero JavaScript, Zero Frameworks).

## Project Overview

- **Project Title:** Veyora - Fashion E-commerce Website
- **Course:** Web Engineering
- **Author:** Safi Raza (BSE-24S-069)
- **Technology Stack:** Pure HTML5 & CSS3
- **Repository URL:** https://github.com/safiraza112/veyora-ecommerce
- **Live Website:** https://veyora-ecommerce-9cflud8s6-safi-raza.vercel.app

## Key Features

**10 Dedicated Semantic Pages:**

- `index.html` - Home with hero banner, categories, featured products, offer banner and newsletter form.
- `shop.html` - Grid of all products with prices in PKR and sale badges.
- `categories.html` - Women, Men, Accessories and Footwear category cards.
- `product.html` - Product details, image gallery, size and colour options, and related products.
- `cart.html` - Sample cart items with an order summary.
- `checkout.html` - Shipping form, payment method choices and order summary.
- `about.html` - Brand story and values.
- `contact.html` - Contact form, studio address and map placeholder.
- `login.html` - Login and registration forms.
- `faq.html` - Pure CSS accordion built with `<details>` and `<summary>`.

**Zero JavaScript Interactivity:**

- **Pure CSS Mobile Navigation:** A hidden checkbox (`#menu-toggle`) and the `:checked` selector open and close the mobile menu.
- **Pure CSS Accordion:** Styled `<details>` and `<summary>` tags with an animated plus icon.
- **Pure CSS Product Options:** Size and colour pickers are radio buttons styled with `:checked`.
- **Native Form Behaviour:** Forms use proper input types, labels and the `required` attribute.

**Design System & Styling:**

- Colour palette: deep aubergine (`#24123a`), plum (`#5b2a86`), marigold (`#f0b429`), rose (`#c94f7c`) and a soft lilac-white background (`#f7f4f9`).
- Fonts: Bodoni Moda for headings and DM Sans for body text (Google Fonts via `<link>`).
- Reusable CSS custom properties (`:root`) for colours, fonts and radius.
- CSS Grid for product and page layouts, Flexbox for the navbar and rows.
- Hover and focus transitions on buttons, cards and links.
- Fully responsive for desktop, tablet and mobile with media queries (900px and 560px).
- Local SVG image files, so the site works offline and has no broken image links.

**Accessibility Basics:**

- Semantic landmarks (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<footer>`).
- Visible `:focus-visible` outline for keyboard users.
- Every form input has a matching `<label for="...">`.
- Alt text on all images and `aria-current="page"` on the active navigation link.
- Reduced-motion support with `prefers-reduced-motion`.

## File Structure

```
veyora-ecommerce/
├── index.html              # Home Page
├── shop.html               # All Products Page
├── categories.html         # Categories Page
├── product.html            # Product Details Page
├── cart.html               # Shopping Cart Page
├── checkout.html           # Checkout Page
├── about.html              # About Page
├── contact.html            # Contact Page
├── login.html              # Login & Register Page
├── faq.html                # FAQ Page
├── css/
│   └── style.css           # Single External Stylesheet
├── images/                 # Local SVG Asset Directory
│   ├── hero.svg            # Home Hero Banner
│   ├── about.svg           # About Page Image
│   ├── cat-women.svg       # Category Images (4 files)
│   ├── p1.svg ... p8.svg   # Product Images (8 files)
│   └── p1-b.svg, p1-c.svg  # Product Colour Views
├── ARCHITECTURE.md         # Architecture Notes
├── README.md               # Project Documentation
└── .gitignore
```

## How to Run the Website Locally

The project uses pure HTML5 and CSS3 with no build steps or dependencies.

**Method 1: Open in Browser (Easiest)**
1. Open the `veyora-ecommerce/` folder.
2. Double-click `index.html`. The site opens in your default browser.

**Method 2: VS Code Live Server**
1. Open the folder in Visual Studio Code.
2. Right-click `index.html` and choose **Open with Live Server**.

**Method 3: Python HTTP Server**

```
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Deployment Instructions (GitHub Pages)

1. Push the code to GitHub:

```
git init
git add .
git commit -m "feat: complete 10-page HTML/CSS e-commerce website"
git branch -M main
git remote add origin https://github.com/safiraza112/veyora-ecommerce.git
git push -u origin main
```

2. Enable GitHub Pages:
   - Open the repository **Settings** and click **Pages**.
   - Under **Build and deployment > Source**, choose **Deploy from a branch**.
   - Select branch `main` and folder `/ (root)`, then click **Save**.

3. After 1 to 2 minutes the site is live at https://safiraza112.github.io/veyora-ecommerce/

## Submission Checklist

- [x] 10 distinct HTML pages
- [x] Same navigation bar and footer on every page
- [x] Active page indicator on the navigation link
- [x] All styles in one external stylesheet: `css/style.css`
- [x] Zero JavaScript and zero frameworks
- [x] Pure CSS mobile hamburger menu (checkbox hack)
- [x] Pure CSS accordion using `<details>` and `<summary>`
- [x] Forms with matching labels, input types and `required`
- [x] Responsive layouts for desktop, tablet and mobile
- [x] Architecture notes in `ARCHITECTURE.md`
- [x] Code on GitHub and deployed with GitHub Pages
