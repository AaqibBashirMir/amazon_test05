<h3>HOSTED LINK:-</h3><br>
https://aaqibbashirmir.github.io/amazon_test05/<br>

![aaaama](https://github.com/AaqibBashirMir/amazon_test05/assets/35392012/2a15cde1-53d0-468e-a608-307d4977f219)<br>
Html
body

"header": This indicates the header section of the webpage.
"nav class='navbar'": Inside the header, this "nav" element signifies the navigation bar.
"div class='nav-logo'": Inside the navbar, this div contains the logo image.
"a href='#'": An anchor link that wraps around the logo image.
"img src='logo_URL' alt='logo'": An image is displayed with a URL and an alt attribute.
"div class='address'": Inside the navbar, this div holds the delivery address information.
"a href='#' class='deliver'": A link for delivery options.
"div class='map-icon'": Inside the address div, this div holds the map icon and location link.
"span class='material-symbols-outlined'": An icon from the Material Symbols Outlined font.
"a href='#' class='location'": A link for the location (India, in this case).

CSS:

header Selector:

Targets the

element.
Sets the width to 100% of its containing element.
Background color is set to a dark grayish color (rgb(15, 17, 17)).
.navbar Class:

Targets elements with the class name "navbar".
Sets a height of 60px for the element.
Uses flex display to horizontally align and distribute items evenly.
Cursor changes to a pointer on hover.
Text color is set to white (#fff).
Maximum width is capped at 1280px, centered with auto margins.

.nav-logo img Selector:

Targets the  element within an element with the class "nav-logo".
Adds 10px margin to the top of the image.
Sets a width of 128px for the image.

.address .deliver Selector:

Targets elements with class "deliver" within an element with class "address".
Adds 20px margin to the left.
Sets font size to 0.75rem (relative to the default font size).
Text color is set to a light gray (#ccc).

.address .map-icon Selector:

Targets elements with class "map-icon" within an element with class "address".
Uses flex display to vertically align the items within.
Aligns items along the center of the cross-axis (horizontally).

<br>
<br>
Html:

Inside the "navbar" section:

"div class='sign-in'": This div represents the "Hello, sign in" section.
"a href='#'": An anchor link wrapping the content for the sign-in section.
"p": A paragraph for "Hello, sign in" text.
"span": A span element with "Account & Lists" text.
"div class='returns'": This div represents the "Returns" section.
"a href='#'": An anchor link wrapping the content for the returns section.
"p": A paragraph for "Returns" text.
"span": A span element with "Orders" text.
"div class='cart'": This div represents the shopping cart section.
"a href='#'": An anchor link wrapping the content for the cart section.
"span class='material-symbols-outlined cart-icon'": An icon from the Material Symbols Outlined font.
"p": A paragraph for "Cart" text.

CSS:

.sign-in p, .returns p Selector:

Targets

elements within elements with class "sign-in" and "returns".
Sets font size to 0.75rem.

.sign-in, .returns span Selector:

Targets elements with class "sign-in" and elements within elements with class "returns".
Sets font size to 0.875rem.
Sets font weight to 600 (bold).

.cart Class:

Targets elements with the class "cart".
Uses flex display to arrange child elements in a row.

.cart .cart-icon Selector:

Targets elements with the class "cart-icon" within elements with the class "cart".
Sets font size to 2.5rem.

.cart p Selector:

Targets

elements within elements with the class "cart".
Adds 20px margin to the top.
Sets font weight to 500 (semi-bold).
