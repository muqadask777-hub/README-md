
# Clothing Store Landing Page - Box Mapping Assignment
## SECTION 1: NAVBAR
[Screenshot: NAVBAR_SECTION_01.png]
| Box Name | HTML Tag | Description |
|---|---|---|
| NAVBAR CONTAINER | <header> | Outermost container for navigation, sticky to top. |
| LOGO | <a> | Clickable brand text (Esprit). |
| NAV LINKS WRAPPER | <nav> > <ul> | Row holding the menu links. |
| CTA BUTTON | <button> | "Buy Now" button on the right edge. |
**CSS Properties:**
| Property | Value | Purpose | Snippet |
|---|---|---|---|
| display | flex | Aligns items horizontally. | header { display: flex; } |
| justify-content | space-between | Pushes items to edges. | justify-content: space-between; |
## SECTION 2: HERO SECTION
[Screenshot: HERO_SECTION_02.png]
| Box Name | HTML Tag | Description |
|---|---|---|
| HERO SECTION | <section> | Holds the large background fashion image. |
| TEXT WRAPPER | <div> | Box holding the text over the image. |
| MAIN HEADING | <h1> | Title text "Clothing Store". |
**CSS Properties:**
| Property | Value | Purpose | Snippet |
|---|---|---|---|
| background-size | cover | Fits image to cover the section perfectly. | background-size: cover; |
## SECTION 3: ABOUT US
[Screenshot: ABOUT_US_SECTION_03.png]
| Box Name | HTML Tag | Description |
|---|---|---|
| ABOUT SECTION | <section> | Full section block with white background. |
| SECTION TITLE | <h2> | Center-aligned title "About Us". |
| CARDS WRAPPER | <div> | Horizontal wrapper holding 3 columns. |
| ABOUT CARD | <div> | Individual card (Image + Text). |
**CSS Properties:**
| Property | Value | Purpose | Snippet |
|---|---|---|---|
| display | flex | Positions 3 cards side-by-side. | div { display: flex; } |
| gap | 24px | Adds spacing between cards. | gap: 24px; |
## SECTION 4: PROMO BANNER (-70%)
[Screenshot: PROMO_BANNER_04.png]
| Box Name | HTML Tag | Description |
|---|---|---|
| PROMO BANNER | <section> | Banner featuring the sale text. |
| INFO WRAPPER | <div> | Centered column grouping details. |
| SHOP BUTTON | <button> | "Shop Now" call to action button. |
**CSS Properties:**
| Property | Value | Purpose | Snippet |
|---|---|---|---|
| flex-direction | column | Stacks items vertically inside the box. | flex-direction: column; |
## SECTION 5: FEATURES OUR STORE
[Screenshot: FEATURES_SECTION_05.png]
| Box Name | HTML Tag | Description |
|---|---|---|
| FEATURES CONTAINER | <section> | Outermost section for features list. |
| LEFT TITLE BOX | <div> | Left column for the heading. |
| RIGHT GRID BOX | <div> | Right column holding 2x2 items grid. |
**CSS Properties:**
| Property | Value | Purpose | Snippet |
|---|---|---|---|
| display | grid | Forms a clean grid for feature icons. | div { display: grid; } |
| grid-template-columns | 1fr 1fr | Splits space into two equal columns. | grid-template-columns: 1fr 1fr; |
## SECTION 6: OUR PRODUCTS
[Screenshot: PRODUCTS_SECTION_06.png]
| Box Name | HTML Tag | Description |
|---|---|---|
| PRODUCTS SECTION | <section> | Main section for displaying clothes catalog. |
| GRID WRAPPER | <div> | Wrapping box for responsive items rows. |
| PRODUCT CARD | <div> | Individual item (Image, Title, Price). |
**CSS Properties:**
| Property | Value | Purpose | Snippet |
|---|---|---|---|
| flex-wrap | wrap | Drops items to next row if space is small. | flex-wrap: wrap; |
## SECTION 7: NEWSLETTER
[Screenshot: NEWSLETTER_SECTION_07.png]
| Box Name | HTML Tag | Description |
|---|---|---|
| NEWSLETTER BOX | <section> | Bottom accent box for email collection. |
| FORM WRAPPER | <form> | Inline row handling inputs and button. |
| EMAIL INPUT | <input> | Input field for typing email. |
**CSS Properties:**
| Property | Value | Purpose | Snippet |
|---|---|---|---|
| border-bottom | 1px solid #000 | Creates minimalist underline look. | input { border-bottom: 1px solid #000; } |

