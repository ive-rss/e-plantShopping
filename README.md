# Paradise Nursery – e-PlantShopping

A shopping cart application for an online plant shop which offers a variety of house plants.

## 🌿 Demo

Live Website: [https://ive-rss.github.io/e-plantShopping/](https://ive-rss.github.io/e-plantShopping/)

## 🛠️ Tech Stack

- **Frontend:** React 18, Vite
- **State Management:** Redux Toolkit, React Redux
- **Styling:** CSS3
- **Deployment:** GitHub Pages (via gh-pages)

## 🚀 Features

- **Landing Page:** Company branding, background image, mission statement, and "Get Started" CTA.
- **Product Catalog:** 
  - Houseplants displayed in intuitive categories.
  - Each plant shows image, name, price, and a one-click “Add to Cart” button.
- **Redux Cart Functionality:**
  - Add/remove/increment/decrement plant quantities.
  - Cart state persists during session; badge count updates in real-time.
  - "Added to Cart" disables when already in cart, re-enables if item is removed.
- **Cart Page:**
  - View all items with images, names, price, per-item and total cost.
  - Change quantities or remove items.
  - “Continue Shopping” and “Checkout” actions (checkout: “Coming Soon!” popup).
- **Header:** Always displays company logo, navigation, and cart icon with live badge.
- **Mobile Responsive:** Adapts to all device sizes.

## 🏗️ Setup & Local Development

```bash
# Clone the repository
git clone https://github.com/ive-rss/e-plantShopping.git
cd e-plantShopping

# Install dependencies
npm install

# Start local server
npm run dev

```
Visit http://localhost:4173/ (default) to view the app locally.
