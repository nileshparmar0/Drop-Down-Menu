# Drop-Down-Menu

Drop Down Menu Project

Description:
This project is a simple HTML and CSS implementation of a drop-down menu. The menu includes multiple items, and one of them ("Resources") has a sub-menu that becomes visible when the user hovers over it. The project demonstrates the use of basic HTML for structure and CSS for styling and interactivity.

Features:
• Responsive Menu Layout: The menu is designed to be centered on the page with a width of 1000px.
• Hover Effects: Menu items change background color when hovered over.
• Drop-Down Submenu: The "Resources" menu item reveals a sub-menu on hover, providing additional links.
• Smooth Transitions: The submenu appears with a smooth transition effect.

Usage:
1. HTML Structure: The main structure of the menu is defined in the index.html file.
• The menu is wrapped in a <div> with the class menu.
• The primary menu items are listed in an unordered list (<ul>).
• The sub-menu for "Resources" is another unordered list nested within the "Resources" list item.

2. CSS Styling: The styling for the menu is defined in the style.css file.
• General styling resets margins, padding, and list styles for a clean layout.
• The menu is styled to be centered on the page with a black background.
• Menu items have white text and change to orangered on hover.
• The sub-menu is hidden by default and revealed with a smooth transition on hover.

File Structure:
• index.html: Contains the HTML structure of the drop-down menu.
• style.css: Contains the CSS styles that control the appearance and behavior of the menu.

How It Works
1. HTML Setup:
• The <ul> element inside the <div class="menu"> contains the main menu items.
• The "Resources" menu item has a nested <ul class="submenu"> which contains the sub-menu items.

2. CSS Styling:
• The .menu class sets the width and background color of the menu.
• The .menu > ul selector styles the primary menu list.
• The .menu > ul > li selector applies padding and sets the position of each menu item.
• The .submenu class positions the sub-menu absolutely and hides it initially.
• The .submenu li selector styles the individual sub-menu items.
• Hover effects are applied using the :hover pseudo-class to change background color and reveal the sub-menu.

Author: 
Nilesh Parmar

• Email: parmar.nil@northeastern.edu
• LinkedIn: [LinkedIn/Nilesh](https://www.linkedin.com/in/nilesh-parmar-/)
• GitHub: https://github.com/nileshparmar0

This project is a simple example to demonstrate basic HTML and CSS skills, perfect for beginners looking to understand how to create interactive menus with sub-menus.
