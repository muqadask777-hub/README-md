`markdown
# Clothing Store Landing Page - Box Mapping Assignment

## Project Overview
This assignment demonstrates the Box Mapping technique for a Clothing Store landing page based on our course guidelines. It breaks down the page layout into nested boxes, semantic HTML tags, and essential CSS properties before coding.

## Complete Page — Section Stack Overview
How the 7 core sections stack vertically inside the `<body>`:

| Section | CSS Properties |
| --- | --- |
| Navbar | display: flex; | position: sticky; |
| Hero Section | min-height: 80vh; | background-size: cover; |
| About Us | display: flex; | gap: 24px; |
| Promo Banner | display: flex; | flex-direction: column; |
| Features Section | display: grid; | grid-template-columns: 1fr 1fr; |
| Our Products | display: flex; | flex-wrap: wrap; |
| Newsletter | display: flex; | border-bottom: 1px solid #000; |

---

## Section-by-Section Detailed Box Mapping

### 🔹 SECTION 1: NAVBAR
![Navbar Screenshot](images/navbar.png)

| Box Name | HTML Tag | Description |
| --- | --- | --- |
| NAVBAR CONTAINER | `<header>` | Outermost container for navigation, sticky to top. |
| LOGO | `<a>` | Clickable brand text (Esprit). |
| NAV LINKS WRAPPER | `<nav> > <ul>` | Row holding the menu links. |
| CTA BUTTON | `<button>` | "Buy Now" button on the right edge. |

### 🔹 SECTION 2: HERO SECTION
![Hero Screenshot](images/hero.png)

| Box Name | HTML Tag | Description |
| --- | --- | --- |
| HERO SECTION | `<section>` | Holds the large background fashion image. |
| TEXT WRAPPER | `<div>` | Box holding the text over the image. |
| MAIN HEADING | `<h1>` | Title text "Clothing Store". |

### 🔹 SECTION 3: ABOUT US
![About Screenshot](images/about.png)

| Box Name | HTML Tag | Description |
| --- | --- | --- |
| ABOUT SECTION | `<section>` | Full section block with white background. |
| SECTION TITLE | `<h2>` | Center-aligned title "About Us". |
| CARDS WRAPPER | `<div>` | Horizontal wrapper holding 3 columns. |

### 🔹 SECTION 4: PROMO BANNER
![Promo Screenshot](images/promo.png)

| Box Name | HTML Tag | Description |
| --- | --- | --- |
| PROMO BANNER | `<section>` | Banner featuring the sale text. |
| INFO WRAPPER | `<div>` | Centered column grouping details. |
| SHOP BUTTON | `<button>` | "Shop Now" call to action button. |

### 🔹 SECTION 5: FEATURES OUR STORE
![Features Screenshot](images/features.png)

| Box Name | HTML Tag | Description |
| --- | --- | --- |
| FEATURES CONTAINER | `<section>` | Outermost section for features list. |
| LEFT TITLE BOX | `<div>` | Left column for the heading. |
| RIGHT GRID BOX | `<div>` | Right column holding 2x2 items grid. |

### 🔹 SECTION 6: OUR PRODUCTS
![Products Screenshot](images/products.png)

| Box Name | HTML Tag | Description |
| --- | --- | --- |
| PRODUCTS SECTION | `<section>` | Main section for displaying clothes catalog. |
| GRID WRAPPER | `<div>` | Wrapping box for responsive items rows. |
| PRODUCT CARD | `<div>` | Individual item (Image, Title, Price). |

### 🔹 SECTION 7: NEWSLETTER
![Newsletter Screenshot](images/newsletter.png)

| Box Name | HTML Tag | Description |
| --- | --- | --- |
| NEWSLETTER BOX | `<section>` | Bottom accent box for email collection. |
| FORM WRAPPER | `<form>` | Inline row handling inputs and button. |
| EMAIL INPUT | `<input>` | Input field for typing email. |

```
