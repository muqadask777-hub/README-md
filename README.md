
# Clothing Store Landing Page - Box Mapping Assignment
Is project mein humne "Box Mapping" technique ka use karte hue ek Clothing Store landing page ka layout structure define kiya hai.
## 1. Section Stack Overview
Landing page ke 7 core sections ka vertical stacking order:
| Section | Key CSS Properties |
|---|---|
| **Navbar** | display: flex;, position: sticky; |
| **Hero Section** | min-height: 80vh;, background-size: cover; |
| **About Us** | display: flex;, gap: 24px; |
| **Promo Banner** | display: flex;, flex-direction: column; |
| **Features Section** | display: flex;, display: grid; |
| **Our Products** | display: flex;, flex-wrap: wrap; |
| **Newsletter** | display: flex;, border-bottom: 1px solid #000; |
## 2. Section-by-Section Box Mapping
### Section 1: Navbar
| Box Name | HTML Tag | Description |
|---|---|---|
| NAVBAR CONTAINER | <header> | Outermost container, sticky to top. |
| LOGO | <a> | Clickable brand text (Esprit). |
| NAV LINKS WRAPPER | <nav> > <ul> | Row holding the menu links. |
| CTA BUTTON | <button> | "Buy Now" button. |
**CSS:** header { display: flex; justify-content: space-between; }
### Section 2: Hero Section
| Box Name | HTML Tag | Description |
|---|---|---|
| HERO SECTION | <section> | Holds background fashion image. |
| TEXT WRAPPER | <div> | Box holding text over image. |
| MAIN HEADING | <h1> | Title text "Clothing Store". |
**CSS:** .hero { background-size: cover; min-height: 80vh; }
### Section 3: About Us
| Box Name | HTML Tag | Description |
|---|---|---|
| ABOUT SECTION | <section> | Full section block. |
| SECTION TITLE | <h2> | Center-aligned title. |
| CARDS WRAPPER | <div> | Horizontal wrapper (3 columns). |
| ABOUT CARD | <div> | Individual card (Image + Text). |
**CSS:** .cards-wrapper { display: flex; gap: 24px; }
### Section 4: Promo Banner
| Box Name | HTML Tag | Description |
|---|---|---|
| PROMO BANNER | <section> | Banner featuring sale text. |
| INFO WRAPPER | <div> | Centered column grouping details. |
| SHOP BUTTON | <button> | "Shop Now" button. |
**CSS:** .info-wrapper { display: flex; flex-direction: column; }
### Section 5: Features Our Store
| Box Name | HTML Tag | Description |
|---|---|---|
| FEATURES CONTAINER | <section> | Outermost section. |
| LEFT TITLE BOX | <div> | Left column for heading. |
| RIGHT GRID BOX | <div> | Right column (2x2 items grid). |
**CSS:** .right-grid { display: grid; grid-template-columns: 1fr 1fr; }
### Section 6: Our Products
| Box Name | HTML Tag | Description |
|---|---|---|
| PRODUCTS SECTION | <section> | Main catalog section. |
| GRID WRAPPER | <div> | Wrapper for responsive rows. |
| PRODUCT CARD | <div> | Individual item (Img, Title, Price). |
**CSS:** .grid-wrapper { display: flex; flex-wrap: wrap; }
### Section 7: Newsletter
| Box Name | HTML Tag | Description |
|---|---|---|
| NEWSLETTER BOX | <section> | Bottom accent box. |
| FORM WRAPPER | <form> | Inline row for input/button. |
| EMAIL INPUT | <input> | Field for email. |
**CSS:** input { border-bottom: 1px solid #000; }

