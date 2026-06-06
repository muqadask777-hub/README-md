Navigation Menu
Sign in
aleesha-tech01
/
box-mapping
Public
Code
Issues
Pull requests
aleesha-tech01/box-mapping
Name	
aleesha-tech01
aleesha-tech01
13 hours ago
README.md
13 hours ago
Repository files navigation
README
Clothing Store Landing Page - Box Mapping Assignment
Project Overview
This assignment demonstrates the Box Mapping technique for a Clothing Store landing page based on our course guidelines. It breaks down the page layout into nested boxes, semantic HTML tags, and essential CSS properties before coding.

Complete Page — Section Stack Overview
How the 7 core sections stack vertically inside the <body>:

Navbar: display: flex; | position: sticky;
Hero Section: min-height: 80vh; | background-size: cover;
About Us: display: flex; | gap: 24px;
Promo Banner: display: flex; | flex-direction: column;
Features Section: display: flex; | display: grid;
Our Products: display: flex; | flex-wrap: wrap;
Newsletter: display: flex; | border-bottom: 1px solid #000;
Section-by-Section Detailed Box Mapping
🔹 SECTION 1: NAVBAR
Screenshot 2026-06-05 091431
2. Box Tree - Parent Child Hierarchy | HTML Tags
Box Name	HTML Tag	Description
NAVBAR CONTAINER	<header>	Outermost container for navigation, sticky to top.
LOGO	<a>	Clickable brand text (Esprit).
NAV LINKS WRAPPER	<nav> > <ul>	Row holding the menu links.
CTA BUTTON	<button>	"Buy Now" button on the right edge.
3. CSS Properties Table
Property	Value	Purpose	Snippet
display	flex	Aligns items horizontally.	header { display: flex; }
justify-content	space-between	Pushes items to edges.	justify-content: space-between;
🔹 SECTION 2: HERO SECTION
Screenshot 2026-06-05 092116
2. Box Tree - Parent Child Hierarchy | HTML Tags
Box Name	HTML Tag	Description
HERO SECTION	<section>	Holds the large background fashion image.
TEXT WRAPPER	<div>	Box holding the text over the image.
MAIN HEADING	<h1>	Title text "Clothing Store".
3. CSS Properties Table
Property	Value	Purpose	Snippet
background-size	cover	Fits image to cover the section perfectly.	background-size: cover;
🔹 SECTION 3: ABOUT US
Screenshot 2026-06-05 093326
2. Box Tree - Parent Child Hierarchy | HTML Tags
Box Name	HTML Tag	Description
ABOUT SECTION	<section>	Full section block with white background.
SECTION TITLE	<h2>	Center-aligned title "About Us".
CARDS WRAPPER	<div>	Horizontal wrapper holding 3 columns.
ABOUT CARD	<div>	Individual card (Image + Text).
3. CSS Properties Table
Property	Value	Purpose	Snippet
display	flex	Positions 3 cards side-by-side.	div { display: flex; }
gap	24px	Adds spacing between cards.	gap: 24px;
🔹 SECTION 4: PROMO BANNER (-70%)
Screenshot 2026-06-05 094056
2. Box Tree - Parent Child Hierarchy | HTML Tags
Box Name	HTML Tag	Description
PROMO BANNER	<section>	Banner featuring the sale text.
INFO WRAPPER	<div>	Centered column grouping details.
SHOP BUTTON	<button>	"Shop Now" call to action button.
3. CSS Properties Table
Property	Value	Purpose	Snippet
flex-direction	column	Stacks items vertically inside the box.	flex-direction: column;
🔹 SECTION 5: FEATURES OUR STORE
Screenshot 2026-06-05 095050
2. Box Tree - Parent Child Hierarchy | HTML Tags
Box Name	HTML Tag	Description
FEATURES CONTAINER	<section>	Outermost section for features list.
LEFT TITLE BOX	<div>	Left column for the heading.
RIGHT GRID BOX	<div>	Right column holding 2x2 items grid.
3. CSS Properties Table
Property	Value	Purpose	Snippet
display	grid	Forms a clean grid for feature icons.	div { display: grid; }
grid-template-columns	1fr 1fr	Splits space into two equal columns.	grid-template-columns: 1fr 1fr;
🔹 SECTION 6: OUR PRODUCTS
Screenshot 2026-06-05 100819
2. Box Tree - Parent Child Hierarchy | HTML Tags
Box Name	HTML Tag	Description
PRODUCTS SECTION	<section>	Main section for displaying clothes catalog.
GRID WRAPPER	<div>	Wrapping box for responsive items rows.
PRODUCT CARD	<div>	Individual item (Image, Title, Price).
3. CSS Properties Table
Property	Value	Purpose	Snippet
flex-wrap	wrap	Drops items to next row if space is small.	flex-wrap: wrap;
🔹 SECTION 7: NEWSLETTER
