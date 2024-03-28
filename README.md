# Module_6_OMPMAR491_BCL2401_Group1E_Omphemetse_Marole_JSL06

# Restaurant Menu System - A Simple Guide

- This code creates a basic restaurant menu system that displays items categorized as Starters, Main Courses, and Desserts.

# What it does:

- Stores menu items in a JavaScript object (menu).
- Displays the menu categories and items on a webpage (requires HTML integration).
- Allows users to add items to their order by clicking on them.
- Tracks the order items and updates a running total price (assumes a base price of R50 per item).

# How to use it:

1. HTML Integration:

- You'll need an HTML file with elements for displaying the menu (menu), order items (order-items), and order total (order-total).
- Make sure these elements have the correct IDs to match the JavaScript code.

2. Include the JavaScript:

- Include this JavaScript file in your HTML document using a <script> tag.

# Technical details:

1. The code uses functions to organize the logic:

- displayMenuItems - Loops through the menu object, creates headings for each category, and displays a list of items within each category.
- addToOrder - Handles adding an item to the order list and updating the total price.
- initMenuSystem - Starts the system by calling displayMenuItems.
- The code assumes a base price of $50 per item. You'll need to modify it if your pricing is different.

# Further enhancements:

1. This is a basic example. You can extend it to:

- Include item descriptions and prices.
- Allow for quantity selection.
- Implement functionality for removing items from the order.
- Connect it to a backend system for order processing and payment.

# challenges

- when i was pressing the item to addToOrder was not running.
