This Project consists of an HTML, CSS, and JavaScript setup for creating a simple calculator with a toggleable dark mode. 

1.HTML (index.html)
The HTML file structures the Calculator interface.

>>Head Section: Contains meta information and links to external CSS and Google Fonts.
>>Body Section:
   .toggleBtn: A small button in the top right corner, used to toggle between dark and light mode.
   .calculator: Container for the calculator UI.
   .buttons: Grid layout for calculator buttons.
   #value: Display area for calculator input and results.
Various <span> elements: Represent calculator buttons for numbers, operations, clear, and equals.


2.CSS (style.css)
The CSS file styles the calculator,making it visually appealine.

>>Global Styles: Resets margin, padding, and box-sizing for all elements. Uses the Montserrat font.
>>Light Mode: Styling for the calculator and its components in light mode.
>>Dark Mode: Applied when .dark class is added to body. Adjusts background colors, text colors,
 and shadows accordingly.


3.JavaScript (script.js)
JavaScript primarily used for creating dynamic and interactive content on web pages.

>>Event Listeners:
Iterates over all <span> elements inside .buttons to handle click events.
Updates the #value element based on button clicks (Clear, numbers, operations).
Toggle Button: Toggles the .dark class on body, which switches between light and dark mode styles defined in style.css.



Summary:
This code creates a functional calculator with basic arithmetic operations and a toggleable dark mode using HTML, CSS, and JavaScript. The calculator's appearance changes dynamically based on the dark mode toggle, demonstrating effective use of CSS for styling and JavaScript for functionality.

# DigitalBhem
