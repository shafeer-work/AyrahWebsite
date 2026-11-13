# Loopsy Land — GitHub Pages storefront

## Site files
- `index.html` — responsive design, abstract motion banner, animated navigation, flip cards and product popup.
- `site-config.json` — brand name, WhatsApp number, developer email and social links.
- `products.json` — product catalogue.
- `product-template.csv` — spreadsheet template.

## Demo contact values
The WhatsApp number is deliberately set to `0000000000` so it cannot accidentally message a real person. The developer email is `webstudio@example.com`. Social profiles use `yourbrand_demo` placeholder handles. Replace these with real details before publishing for customers.

## Update brand and links
Edit `site-config.json`. `brandName` updates the header, hero and page title. `whatsappNumber` must contain digits only, including country code. Set `developerEmail` and the full social URLs for YouTube, Instagram, X, Facebook and Snapchat.

## Excel product list
When an Excel file is uploaded, its rows can be converted into `products.json`. Recommended columns: Item Code, Item Name, Category, Type, Description, Price, Crafting Time, Yarn Type, Colours, Availability, Image Filename and Active. Use unique item codes. Upload photos into `assets/products/` and set each row's relative path in the `image` field. Set Active to false to hide a product.

WhatsApp order messages include product name, item code, price, crafting time, yarn type and a public photo URL/details link. WhatsApp click-to-chat does not attach the image file automatically.

GitHub Pages serves the static site from the repository root. No build step is required.
