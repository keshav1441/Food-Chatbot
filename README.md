# Fast Food Website with Embedded Chatbot

This project is a simple fast food restaurant website featuring an embedded **Dialogflow** chatbot. The chatbot is fixed in the bottom-left corner of the screen, providing continuous access to users for placing orders, asking questions, and getting information about the restaurant.

## Features

- **Responsive Website Design**: 
  - Includes sections for Home, Menu, Location, and Contact Us.
  - Menu section with images for food items.
  - Embedded map widget for the restaurant's location.
  - Contact information for phone and email inquiries.
  
- **Embedded Dialogflow Chatbot**:
  - Fixed at the bottom-right corner with a `z-index` of 1 for high visibility.
  - Helps users interact with the restaurant for order-related queries.

- **Technologies Used**:
  - **HTML**: For the structure of the website.
  - **CSS**: For styling and responsiveness.
  - **Dialogflow**: Chatbot integrated via an `<iframe>`.

https://github.com/user-attachments/assets/9a173d95-b79b-4604-8ddb-2c81a78c3fde

## How to Use

1. Open the `index.html` file in your browser.
2. The chatbot will be visible in the bottom-right corner, always accessible for user interaction.
3. The website contains interactive sections like the menu and contact information.

## Customization

- **Menu Items**: 
  - You can change the images and descriptions of menu items by editing the `menu` section in the `index.html`.
  
- **Contact Information**: 
  - Update the phone number or email address in the `contactus` section.

- **Chatbot**: 
  - The Dialogflow bot is embedded using an `<iframe>`. You can change the bot's Dialogflow project by replacing the `iframe` source with the appropriate Dialogflow URL.



