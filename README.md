

Clothing Store Landing Page - Box Mapping Assignment

Project Overview

This assignment demonstrates the Box Mapping technique for a Clothing Store landing page based on course guidelines. It breaks down the page layout into nested boxes, semantic HTML tags, and essential CSS properties before coding.

---

Complete Page — Section Stack Overview

How the 7 core sections stack vertically inside the "<body>":

Section| Important CSS Properties
Navbar| "display: flex;" | "position: sticky;"
Hero Section| "min-height: 80vh;" | "background-size: cover;"
About Us| "display: flex;" | "gap: 24px;"
Promo Banner| "display: flex;" | "flex-direction: column;"
Features Section| "display: flex;" | "display: grid;"
Our Products| "display: flex;" | "flex-wrap: wrap;"
Newsletter| "display: flex;" | "border-bottom: 1px solid #000;"

---

Section-by-Section Detailed Box Mapping

---

🔹 SECTION 1: NAVBAR

Screenshot

"Navbar" (images/navbar.png)

Box Tree - Parent Child Hierarchy | HTML Tags

Box Name| HTML Tag| Description
NAVBAR CONTAINER| "<header>"| Outermost container for navigation, sticky to top.
LOGO| "<a>"| Clickable brand text (Esprit).
NAV LINKS WRAPPER| "<nav>" > "<ul>"| Row holding the menu links.
CTA BUTTON| "<button>"| "Buy Now" button on the right edge.

CSS Properties Table

Property| Value| Purpose| Snippet
display| flex| Aligns items horizontally.| "header { display: flex; }"
justify-content| space-between| Pushes items to edges.| "justify-content: space-between;"

---

🔹 SECTION 2: HERO SECTION

Screenshot

"Hero Section" (images/hero-section.png)

Box Tree - Parent Child Hierarchy | HTML Tags

Box Name| HTML Tag| Description
HERO SECTION| "<section>"| Holds the large background fashion image.
TEXT WRAPPER| "<div>"| Box holding the text over the image.
MAIN HEADING| "<h1>"| Title text "Clothing Store".

CSS Properties Table

Property| Value| Purpose| Snippet
background-size| cover| Fits image to cover the section perfectly.| "background-size: cover;"

---

🔹 SECTION 3: ABOUT US

Screenshot

"About Us" (images/about-us.png)

Box Tree - Parent Child Hierarchy | HTML Tags

Box Name| HTML Tag| Description
ABOUT SECTION| "<section>"| Full section block with white background.
SECTION TITLE| "<h2>"| Center-aligned title "About Us".
CARDS WRAPPER| "<div>"| Horizontal wrapper holding 3 columns.
ABOUT CARD| "<div>"| Individual card (Image + Text).

CSS Properties Table

Property| Value| Purpose| Snippet
display| flex| Positions 3 cards side-by-side.| "div { display: flex; }"
gap| 24px| Adds spacing between cards.| "gap: 24px;"

---

🔹 SECTION 4: PROMO BANNER (-70%)

Screenshot

"Promo Banner" (images/promo-banner.png)

Box Tree - Parent Child Hierarchy | HTML Tags

Box Name| HTML Tag| Description
PROMO BANNER| "<section>"| Banner featuring the sale text.
INFO WRAPPER| "<div>"| Centered column grouping details.
SHOP BUTTON| "<button>"| "Shop Now" call to action button.

CSS Properties Table

Property| Value| Purpose| Snippet
flex-direction| column| Stacks items vertically inside the box.| "flex-direction: column;"

---

🔹 SECTION 5: FEATURES OUR STORE

Screenshot

"Features Section" (images/features-section.png)

Box Tree - Parent Child Hierarchy | HTML Tags

Box Name| HTML Tag| Description
FEATURES CONTAINER| "<section>"| Outermost section for features list.
LEFT TITLE BOX| "<div>"| Left column for the heading.
RIGHT GRID BOX| "<div>"| Right column holding 2×2 items grid.

CSS Properties Table

Property| Value| Purpose| Snippet
display| grid| Forms a clean grid for feature icons.| "div { display: grid; }"
grid-template-columns| 1fr 1fr| Splits space into two equal columns.| "grid-template-columns: 1fr 1fr;"

---

🔹 SECTION 6: OUR PRODUCTS

Screenshot

"Products Section" (images/products-section.png)

Box Tree - Parent Child Hierarchy | HTML Tags

Box Name| HTML Tag| Description
PRODUCTS SECTION| "<section>"| Main section for displaying clothes catalog.
GRID WRAPPER| "<div>"| Wrapping box for responsive item rows.
PRODUCT CARD| "<div>"| Individual item (Image, Title, Price).

CSS Properties Table

Property| Value| Purpose| Snippet
flex-wrap| wrap| Drops items to next row if space is small.| "flex-wrap: wrap;"

---

🔹 SECTION 7: NEWSLETTER

Screenshot

"Newsletter" (images/newsletter.png)

Box Tree - Parent Child Hierarchy | HTML Tags

Box Name| HTML Tag| Description
NEWSLETTER SECTION| "<section>"| Newsletter subscription area.
CONTENT WRAPPER| "<div>"| Holds heading and input field.
EMAIL INPUT| "<input>"| User enters email address.
SUBSCRIBE BUTTON| "<button>"| Submit subscription request.

CSS Properties Table

Property| Value| Purpose| Snippet
display| flex| Aligns content horizontally.| "display: flex;"
border-bottom| 1px solid #000| Creates bottom separator line.| "border-bottom: 1px solid #000;"

---

