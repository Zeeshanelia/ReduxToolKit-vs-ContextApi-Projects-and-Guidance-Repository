# Click Shop Online Store —  E-Commerce Web App

A modern, full-featured e-commerce application built with React, featuring product browsing, category filtering, cart management, and user authentication.

## 🚀 Tech Stack
• Context API   • Axios     • React Router DOM    • Clerk Auth    • DummyJSON API

- npm install react-slick
- npm i lottie-react
- npm i react-toastify
- npm i lucide react

##  Features
- Browse 194+ products with search, filter by category & brand, and price range sorting
- Image carousel on homepage with auto-sliding product highlights
- Single product detail page with quantity selector and Add to Cart
- Persistent shopping cart with localStorage — survives page refresh
- Real-time cart quantity update and item removal with toast notifications
- User authentication (Sign In / Sign Up) powered by Clerk
- Geolocation-based address detection using Geoapify API
- Fully responsive design — mobile-friendly with animated hamburger nav
- Category-based product pages with loading states and Lottie animations
- Checkout page with delivery form, bill summary, promo code input, and grand total

## 📁 Project Structure

src/
├── component/  # Navbar, Footer, ProductCart, FilterSection, Category, Pagination
├── context/    # DataContext (products), CartContext (cart + localStorage)
├── page/       # Home, Product, SingleProduct, CategoryProduct, Cart, About, Contact
└── assets/     # Lottie JSON animations
public/
└── images/     # Logo, banner, loading video


## Environment Variables

VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_GEOAPIFY_KEY=your_geoapify_key


##  Getting Started

git clone https://github.com/...
cd Click-Shop-Online-Store
npm install
npm run dev
