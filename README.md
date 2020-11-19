# Pricing Product Page
Learning opportunity to create a product page using vanilla HTML and CSS
Final output can be found here: https://akhuu92.github.io/pricingProductPage/

# Notes (What did I learn?)
Why does nav need a display of flex?
- In order to put all items (within the nav) on the same line

Why do we set a display of inline on the nav-items li?
- In order to have the nav items horizontal instead of vertical
- Targeting the group (nav-items) will NOT order put each individual li(s) next to each other
- inline: The element generates one or more inline element boxes that do not generate line breaks before or after themselves. 

Margin vs Padding:
- Margin is white space outside of the element
- Padding is white space inside of the element

Created a div (main-container) to house everything
Created a div within main-container to house buttons
- A main div group for buttons
- Then individual divs for the buttons themselves

In order to move the buttons down (away from nav items)
- Need to add margin-top on the main div for the buttons (move everything down)

In order to create a small space between buttons
- Need to a margin for the button themselves

In order to display buttons
- Add unique class to each button and change background color

Why does adding a p underneath a h1 push the text outside of the button?
- h1 naturally contains margin
- In styles.css, set margin for h1 to 0 to fix this issue
- Naturally, p also has margins by default. Removing both will keep text closer
- Modifying padding does NOT keep text closer

Created a div within main-container to house the cards (card-container)
Created a div within card-container for each card (base-card)
- A main div group for cards
- Then individual divs for the cards themselves

Inside the card, would like to modify the header
- Create a div to includes img, h1, and small

What if I want to add space between the image and h1 and small?
- Create another div to house the h1 and small separately
- Now you can padding to move them away

Create a div (card-content) to house contents for the cards
- ul in order to  list out items
- Add padding to make it line up with icon in header

How can I line up icon with li text?
- display: flex

How can I add space between icon and li text?
- Made li text a span
- Added padding-left to add space between icon and text

Created a div (footer) to house info for price as well as button. Maybe a better class name could be used
- A div for price
- A div for the button

How can I line up the h1 with the h6?
- display: flex!
- align-item in order to keep items centered
- Padding to create space between info

How can I keep p in the center of the button?
- again, display: flex!

# Credit
Followed along: https://www.youtube.com/watch?v=ooPHanwHBEY
