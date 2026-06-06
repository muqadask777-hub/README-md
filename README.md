

# Clothing Store Landing Page - Box Mapping Assignment

## Project Overview
This assignment demonstrates the Box Mapping Technique for a Clothing Store Landing Page. The layout is divided into sections and analyzed using Parent-Child hierarchy, semantic HTML tags, and CSS properties before implementation.

## Complete Page — Section Stack Overview
| Section | Important CSS Properties |
|---|---|
| Navbar | display: flex; position: sticky; |
| Hero Section | min-height: 80vh; background-size: cover; |
| About Us | display: flex; gap: 24px; |
| Promo Banner | display: flex; flex-direction: column; |
| Features Section | display: grid; grid-template-columns: 1fr 1fr; |
| Our Products | display: flex; flex-wrap: wrap; |
| Newsletter | display: flex; border-bottom: 1px solid #000; |

## 🔹 SECTION 1: NAVBAR
### 1. Screenshot
<img width="844" height="375" alt="navbar png1" src="https://github.com/user-attachments/assets/89f6807a-db2a-4902-9f85-698e6605fed9" />
### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
|---|---|---|
| NAVBAR CONTAINER | `<header>` | Outermost container for navigation. |
| LOGO | `<a>` | Clickable brand logo text. |
| NAV LINKS WRAPPER | `<nav> > <ul>` | Holds menu links. |
| CTA BUTTON | `<button>` | Buy Now button. |
### 3. CSS Properties Table
| Property | Value | Purpose |
|---|---|---|
| display | flex | Aligns items horizontally. |
| justify-content | space-between | Pushes content to opposite sides. |

## 🔹 SECTION 2: HERO SECTION
### 1. Screenshot
<img width="546" height="346" alt="Screenshot 2026-06-06 132118" src="https://github.com/user-attachments/assets/0ed63801-85bb-43ad-a334-d949ee50d490" />
### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
|---|---|---|
| HERO SECTION | `<section>` | Main banner area. |
| TEXT WRAPPER | `<div>` | Contains hero text. |
| MAIN HEADING | `<h1>` | Main title of page. |
### 3. CSS Properties Table
| Property | Value | Purpose |
|---|---|---|
| background-size | cover | Covers entire hero area. |
| min-height | 80vh | Creates large banner height. |

## 🔹 SECTION 3: ABOUT US
### 1. Screenshot
<img width="553" height="320" alt="Screenshot 2026-06-06 132225" src="https://github.com/user-attachments/assets/35110a85-42f5-427f-8d40-dd4e260f3a5f" />
### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
|---|---|---|
| ABOUT SECTION | `<section>` | Main about section. |
| SECTION TITLE | `<h2>` | About Us heading. |
| CARDS WRAPPER | `<div>` | Holds three cards. |
| ABOUT CARD | `<div>` | Individual content card. |
### 3. CSS Properties Table
| Property | Value | Purpose |
|---|---|---|
| display | flex | Places cards side-by-side. |
| gap | 24px | Adds spacing between cards. |

## 🔹 SECTION 4: PROMO BANNER
### 1. Screenshot
<img width="670" height="321" alt="Screenshot 2026-06-06 132448" src="https://github.com/user-attachments/assets/d1efafbf-40b8-4269-a34d-e7b793298717" />
### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
|---|---|---|
| PROMO BANNER | `<section>` | Promotional sale section. |
| INFO WRAPPER | `<div>` | Groups text content. |
| SHOP BUTTON | `<button>` | Shop Now CTA button. |
### 3. CSS Properties Table
| Property | Value | Purpose |
|---|---|---|
| display | flex | Enables flexible layout. |
| flex-direction | column | Stacks content vertically. |

## 🔹 SECTION 5: FEATURES OUR STORE
### 1. Screenshot
<img width="699" height="291" alt="Screenshot 2026-06-06 132928" src="https://github.com/user-attachments/assets/4e85b7ff-0053-4612-80a1-70bd7cc565a4" />
### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
|---|---|---|
| FEATURES CONTAINER | `<section>` | Main features section. |
| LEFT TITLE BOX | `<div>` | Contains heading. |
| RIGHT GRID BOX | `<div>` | Holds feature items. |
### 3. CSS Properties Table
| Property | Value | Purpose |
|---|---|---|
| display | grid | Creates structured grid layout. |
| grid-template-columns | 1fr 1fr | Creates two equal columns. |

## 🔹 SECTION 6: OUR PRODUCTS
### 1. Screenshot
<img width="397" height="370" alt="Screenshot 2026-06-06 133047" src="https://github.com/user-attachments/assets/6f2a5dd0-753e-469d-a95d-afbd377115d5" />

### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
|---|---|---|
| PRODUCTS SECTION | `<section>` | Product catalog area. |
| GRID WRAPPER | `<div>` | Wraps product cards. |
| PRODUCT CARD | `<div>` | Single product item. |
### 3. CSS Properties Table
| Property | Value | Purpose |
|---|---|---|
| display | flex | Aligns product cards. |
| flex-wrap | wrap | Moves cards to next line when needed. |

## 🔹 SECTION 7: NEWSLETTER
### 1. Screenshot
<img width="748" height="355" alt="Screenshot 2026-06-06 133129" src="https://github.com/user-attachments/assets/8fde53da-90e3-4963-8d47-17ed54728c3c" />

### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
|---|---|---|
| NEWSLETTER BOX | `<section>` | Bottom section for email subscription. |
| FORM WRAPPER | `<form>` | Handles input and button layout. |
| EMAIL INPUT | `<input>` | User email input field. |
| SUBSCRIBE BUTTON | `<button>` | Newsletter subscribe button. |
### 3. CSS Properties Table
| Property | Value | Purpose |
|---|---|---|
| display | flex | Aligns form elements horizontally. |
| border-bottom | 1px solid #000 | Creates bottom border effect. |
