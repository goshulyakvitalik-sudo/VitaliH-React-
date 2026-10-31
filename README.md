# 📱 Nice Gadgets Store

A modern, responsive e-commerce application designed for browsing, filtering, and ordering electronic devices and accessories. Built with **React** following Figma design specifications, featuring modular components, dynamic client-side routing, and responsive layouts.

---

## 🔗 Live Demo

- **Live Application:** [Nice Gadgets Online Store](https://goshulyakvitalik-sudo.github.io/VitaliH-React-/)

---

## 🛠 Tech Stack

- **Core Library:** React (Hooks, Context API, Modular Components)
- **Routing:** React Router DOM (dynamic product routes, categories, and query parameters)
- **Language:** JavaScript (ES6+) / TypeScript
- **Styling:** SCSS / Sass Modules (BEM methodology, Flexbox, CSS Grid)
- **Icons & Graphics:** SVG vector icons and responsive imagery
- **Build Tools:** Vite / Create React App, npm
- **Code Standards:** ESLint, Stylelint, Prettier

---

## ✨ Key Features

- **Home Page & Promotional Sliders:**
  - Responsive hero banner carousel with pagination indicators.
  - Curated product carousels: **Hot Prices** and **Brand New Models**.
- **Product Catalogs & Categories:**
  - Dedicated catalog views for **Phones**, **Tablets**, and **Accessories**.
  - Product cards featuring quick technical specifications, current pricing, and discounts.
- **Sorting, Filtering & Pagination:**
  - Real-time catalog sorting (Newest, Alphabetically, Price: Low to High / High to Low).
  - Dynamic pagination with selectable page size (4, 8, 16, All).
  - Live query-based search bar synchronized with URL search params.
- **Cart & Favorites System:**
  - Global shopping cart and favorites management powered by React Context.
  - Persistent state saved to `localStorage`.
  - Real-time item count badges and total price calculation.
- **Product Details View:**
  - Multi-image gallery with interactive thumbnail previews.
  - Attribute selectors (color variations, storage capacity).
  - Comprehensive technical specifications table.
- **Responsive Layout:**
  - Fluid, mobile-first design adapted for smartphones, tablets, and desktop displays.

---

## 💻 Getting Started

Follow these steps to run the project locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/goshulyakvitalik-sudo/VitaliH-React-.git
   cd react_phone-catalog
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm start
   # or
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) (or the port displayed in your terminal) in your browser.

---

## 🏗 Project Structure

```text
src/
├── assets/          # Icons, illustrations, and static files
├── components/      # Shared UI components (Header, Footer, Card, Slider, Pagination)
├── context/         # React Context state providers (CartContext, FavoritesContext)
├── pages/           # Application views (Home, Phones, Tablets, ProductDetails, Cart)
├── services/        # Data fetching services, API utilities, helpers
├── styles/          # Global styles, SCSS variables, mixins, resets
├── types/           # Type definitions / interfaces
├── App.jsx          # Route configuration and layout wrapper
└── index.jsx        # Root application entry point
```

---

## 👨‍💻 Author

Developed by **Vitalii Hoshuliak**
- GitHub: [@goshulyakvitalik-sudo](https://github.com/goshulyakvitalik-sudo)
