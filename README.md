# STD_WD_1
**Task 1:** Create an interactive navigation menu that changes color or style when scrolled or when hovering over a menu item. The navigation menu should have a fixed position and be visible on all pages. Use HTML to structure the menu, CSS to style it, and JavaScript to add interactivity, such as changing the background color or font color of the menu when it is scrolled or when a menu item is hovered over.My project from completely Web Development Development

**Website Link:** https://maskeshravani.github.io/STD_WD_1/

**Learnings from the Project:**

**Header:**
Utilized display: flex to easily apply properties such as justify-content and position for better alignment and positioning.
Employed flex in the navigation section to align items on a single line, particularly useful for block elements arranged vertically.
Integrated transitions to facilitate smooth visual changes within the interface.
**Image Alignment:**
Wrapped the image in a div and utilized text-align to center-align it, enhancing visual aesthetics.
**Footer:**
Positioned the footer at the bottom with bottom: 0, ensuring it aligns at the page's bottom irrespective of its content.
Chose position: relative to avoid using absolute, preventing it from being relative to an image and ensuring it aligns at the page bottom.
**JavaScript Usage:**
Employed JavaScript to dynamically change the header's color by creating a new class, navbar-scrolled, not initially declared in HTML.
Strategically ordered the CSS rules, beginning with the new class, followed by other elements like .navbar li a, allowing easy modification of their properties.
**Dropdown Menu:**
Implemented a dropdown menu within the "Services" list using ul, li, and a elements, assigning a class to the ul.
Initially set display: none and position: absolute for the dropdown, ensuring it stays hidden and appears below its ancestor, "Services."
On hover, changed display to block to reveal the dropdown beneath, preventing it from appearing beside "Services" by avoiding the use of flex.
Extended the dropdown functionality to the scrolling properties, ensuring consistent behavior even with class changes.
