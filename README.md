# Loopsy Land — GitHub Pages storefront

## Site files
- `index.html` — responsive design, animation, product flip cards and detail popup.
- `site-config.json` — brand name, tagline, WhatsApp number, developer email and social links.
- `products.json` — product catalogue consumed by the website.
- `product-template.csv` — a basic spreadsheet template for the catalogue.

## Update brand settings
Edit `site-config.json`. Change `brandName` to rename the header, hero, page title and footer. Add full URLs to `socialLinks` for YouTube, Instagram, X, Facebook and Snapchat; blank URLs are hidden. The WhatsApp number is digits only, with country code.

## Update products from Excel
When you upload an Excel file, its rows can be converted into `products.json`. Recommended columns: Item Code, Item Name, Category, Type, Description, Price, Crafting Time, Yarn Type, Colours, Availability, Image Filename, Active. Keep item codes unique. Put product photos in `assets/products/` and store their relative path in the product `image` field. Set Active to false to hide an item.

## WhatsApp orders
The order button pre-fills WhatsApp with product name, item code, price, crafting time, yarn type, an accessible photo URL (if provided) or product-detail URL, and the product page URL. WhatsApp click-to-chat can share an image link but cannot attach the image file automatically.

GitHub Pages serves this static site from the repository root. No build step or package installation is required.
