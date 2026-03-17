# Nice Gadgets — Phone Catalog

A fully functional **React product catalog** for the Nice Gadgets store, featuring phones, tablets, and accessories — with shopping cart, favorites, and detailed product pages.

## Live Preview
**Live Demo:** [View the live website here](https://seemsgood78.github.io/Phone-catalog/)

## Design Reference
**Figma Link:** [Phone Catalog Design](https://www.figma.com/file/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog-(V2)-Original)

## Technologies Used 💻

**Core**
* **React** (v18.3.1) — UI framework
* **TypeScript** (v5.2.2) — Type safety
* **SCSS** (v1.77.8) — Styling

**State Management**
* **Redux Toolkit** (v2.11.2) — Application state

**UI/UX**
* **React Router DOM** (v6.25.1) — Navigation

**Development & Deployment**
* **Vite** (v5.3.1) — Build tool
* **ESLint + Prettier + Stylelint** — Code quality and formatting
* **GitHub Pages** — Hosting and deployment

## Getting Started

Follow these instructions to set up the project locally:

1. **Clone the repository:**
```bash
git clone https://github.com/SeemsGood78/Phone-catalog.git
cd Phone-catalog
```

2. **Install dependencies:**
```bash
npm install
```

3. **Run the project locally:**
```bash
npm run start
```

## Features

* **Home Page:** Auto-playing banner slider (ignore silly images), Brand New and Hot Prices product sliders, and Shop by Category section (Phones, Tablets, Accessories).
* **Product Catalog Pages:** Browse Phones, Tablets, and Accessories with sorting (Newest, Alphabetically, Cheapest) and pagination — saved to the URL.
* **Product Details Page:** Full specs, available colors and capacities, image gallery, breadcrumbs, and a "You may also like" section.
* **Shopping Cart:** Add/remove products, adjust quantities, auto-calculated totals — persisted to `localStorage`.
* **Favorites Page:** Save and manage favorite products with a heart button — persisted to `localStorage`.
* **Sticky Header & Footer:** Navigation with live cart and favorites counters, Back to Top button.
* **404 Not Found Page:** Handles all unknown routes gracefully.
