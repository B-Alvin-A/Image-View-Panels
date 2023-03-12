# Image-View-Panels
This is HTML/CSS/JavaScript code for an image panel.

The HTML code creates an unordered list (ul) with three list items (li). Each list item contains an image (img) and a span element that shows an icon when hovered over. The images are sourced from a folder named "img" in the same directory as the HTML file.

The CSS code styles the body to be centered, with a blue background color. The unordered list is also centered with a gap of 50 pixels between each list item. Each list item has a height of 500 pixels and a width of 100 pixels, with a border-radius of 100 pixels to create a circular shape. The images inside each list item are set to cover the entire list item and are centered. The span element inside each list item is positioned at the bottom of the list item, with a white background color that has 60% opacity. The icon inside the span is also styled. When the span is hovered over, the cursor changes and the background color changes to a darker blue color with white text.

The JavaScript code selects all elements with class "card-item span" and adds event listeners for when the element is hovered over and when the pointer is removed. When the element is hovered over, it adds the class "open" to the parent element, and when the pointer is removed, it removes the class "open" from the parent element. The "open" class increases the width of the list item to 400 pixels, changes the border-radius to 20 pixels, removes the grayscale filter, and adds a blue box-shadow.
