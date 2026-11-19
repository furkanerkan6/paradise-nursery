# Paradise Nursery

Paradise Nursery is an online plant shop built with **React** and **Redux Toolkit**.

## Features
- **Landing page** with a background image, company name, a paragraph about the company and a *Get Started* button.
- **Product listing page** with 18 houseplants grouped into three categories (Air Purifying, Aromatic, Low Maintenance). Each plant shows a thumbnail, name, description and price, plus an *Add to Cart* button that becomes disabled once the plant is in the cart.
- **Shopping cart page** showing each plant's thumbnail, name, unit price and subtotal, with increase / decrease / delete buttons, total number of plants, total cost, *Continue Shopping* and *Checkout* (Coming Soon) buttons.
- **Navbar** on the product and cart pages with links to Home, Plants and Cart and a cart icon showing the live item count.

## Tech
- React 18 + Vite
- Redux Toolkit (`CartSlice.jsx`, `store.js`)
- Deployed with GitHub Pages

## Run locally
```bash
npm install
npm run dev
```

## Deploy
```bash
npm run deploy
```
