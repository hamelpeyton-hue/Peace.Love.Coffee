[README.md](https://github.com/user-attachments/files/33182083/README.md)

# Peace Love Coffee — website source

## Open the website
Unzip this folder and open index.html in your browser. No installation is required.
For a local web server, run `python3 -m http.server 8000` in the extracted folder and visit http://localhost:8000.

## Edit the website
- index.html: page sections, navigation, story, location, and hours.
- styles.css: colors, fonts, spacing, and mobile layouts.
- app.js: menu products and prices, drink options, shopping bag, and event descriptions.
- assets/: website images.

Change the products array near the top of app.js to edit menu items. Change the events object to edit event details.
Replace images in assets/ and update the image paths in index.html and app.js to use your original drink photos.

## Current functionality
Menu category filters, menu search, drink customization, quantity selection, an editable shopping bag, event details, and responsive navigation.

## Backend and checkout
This is a static website with browser-side JavaScript. It does not have a server, database, payment integration, or real order submission. The shopping bag lasts only for the current page session. Checkout is explicitly a demo.
The address, added menu items, and event calendar are concept content to confirm before business use. Image assets were generated for this website and can be replaced with your own.

## Fonts
The stylesheet loads Archivo Black and DM Sans from Google Fonts. Arial fallbacks are included for offline use.
