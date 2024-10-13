# Responsive Navbar Project
This project implements a responsive navigation bar with social media icons and links using HTML, CSS, and JavaScript. The navbar is designed to be fully responsive, showing a hamburger toggle button on smaller screens (e.g., mobile) to reveal navigation links.

## Features
- Responsive Design: The navigation bar adjusts to different screen sizes.
- Hamburger Menu: On smaller screens, the navigation links are hidden and can be toggled using a button with a hamburger icon.
- Social Media Links: Includes icons for social media platforms like Facebook, Twitter, Behance, LinkedIn, and Sketch.
- FontAwesome Integration: Utilizes FontAwesome for icons.

## Demo
#### Large Screens
On larger screens (e.g., desktop):

The navigation links are visible by default.
The toggle button (hamburger menu) is hidden.

#### Small Screens
On smaller screens (e.g., mobile):

The navigation links are hidden by default.
- A toggle button is displayed to allow users to show or hide the navigation links.

## Files
index.html: Contains the HTML structure of the navbar, including the toggle button, links, and social media icons.
styles.css: Includes the CSS styles for the layout, responsiveness, and visibility of the toggle button and navbar.
app.js: Implements the JavaScript functionality to toggle the visibility of the navigation links when the button is clicked.

## Code Explanation
#### HTML Structure (index.html)
The HTML includes a nav element containing:
- A logo inside a div with the class nav-header.
- A hamburger menu button (<button `class="nav-toggle"`>) that toggles the visibility of the links on smaller screens.
- An unordered list of navigation links (`<ul class="links">`).
- A list of social media icons with anchor links (`<ul class="social-icons">`).

#### CSS (styles.css)
- Media Queries: The layout changes based on screen size using media queries. On screens wider than 768px, the links are shown by default, and the toggle button is hidden. On smaller screens, the links are hidden, and the toggle button is displayed.

## Responsive Design: Flexbox is used for centering and layout management.

#### JavaScript (app.js)
Adds event listeners to the toggle button:
When clicked, it toggles the class show-links on the navigation links list (`<ul class="links">`), controlling whether the links are visible on small screens.
Toggle Functionality: The classList.toggle() method is used to show or hide the links dynamically.