# 🛍️ Adda94 — India's Premium E-Commerce Store

> A fully functional, premium-looking e-commerce web application built for college submission.

---

## 🚀 Features

### 🛒 Shopping
- **34 real products** across 8 categories: Men's, Women's, Electronics, Accessories, Footwear, Beauty, Home & Sports
- Product detail pages with image gallery, size/colour selector, quantity picker
- Add to cart, wishlist, quick-add from listing
- Pincode delivery check
- Product reviews & ratings
- "You May Also Like" section

### 🏠 Home Page
- Full premium hero section with stats
- Live countdown flash sale timer
- Trending & New Arrivals grids
- Category tiles with hover effects
- Promo banners, testimonials
- Animated marquee strip
- Newsletter signup
- Full footer with social links & payment icons

### 🔍 Shop Page
- Filter by price range, rating, brand
- Sort by relevance, price, rating, newest
- Category filtering from navbar
- Live search with dropdown results

### 🛒 Cart
- Add/remove/update quantities
- Coupon codes: **ADDA94**, **SAVE20**, **WELCOME15**, **FIRST50**
- Auto delivery charge calculation (free above ₹999)
- Savings summary

### 💳 Checkout (Simulated — no real payments)
- Full address form with Indian states
- 5 payment modes: UPI, Card, Net Banking, EMI, Cash on Delivery
- Visual payment UI (no real gateway — college-safe)
- Order placed → unique Order ID generated

### 📦 Order Tracking
- Animated order success page
- Step-by-step tracking timeline
- Order history in profile

### 👤 Account
- Login / Signup / Social auth (simulated)
- User profile with order history
- Wishlist & cart count overview

### ⚙️ Admin Dashboard
- Revenue, Orders, Customers, Products stats
- Sales bar chart (monthly)
- Recent orders table with status badges
- Top products list
- Product management grid

---

## 📁 File Structure

```
adda94/
├── index.html          ← Main app (all pages)
├── netlify.toml        ← Netlify deployment config
├── vercel.json         ← Vercel deployment config
├── README.md
├── css/
│   ├── variables.css   ← Design tokens & CSS variables
│   ├── base.css        ← Reset, utilities, product cards
│   ├── navbar.css      ← Navigation styles
│   ├── home.css        ← Hero, categories, flash sale, footer
│   └── pages.css       ← Shop, cart, checkout, auth, admin
└── js/
    ├── data.js         ← All 34 products data
    ├── store.js        ← State management, cart, wishlist, toast
    ├── home.js         ← Home page rendering, flash timer
    ├── shop.js         ← Shop page, filters, sort
    ├── product.js      ← Product detail page
    ├── cart.js         ← Cart rendering & logic
    ├── checkout.js     ← Checkout & order placement
    ├── auth.js         ← Login, signup, profile
    ├── wishlist.js     ← Wishlist rendering
    └── admin.js        ← Admin dashboard
```

---

## 🌐 Deploy to Netlify (Free)

1. Go to [netlify.com](https://netlify.com) → Sign up free
2. Click **"Add new site"** → **"Deploy manually"**
3. Drag and drop the entire `adda94/` folder
4. Your site is live instantly! Example: `https://adda94.netlify.app`

## 🌐 Deploy to Vercel (Free)

1. Push the `adda94/` folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → Import the repo
3. Click **Deploy** — done!

---

## 🎨 Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 (semantic) |
| Styling | CSS3 (custom properties, grid, flexbox, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Playfair Display + DM Sans |
| Icons | Font Awesome 6 |
| Data | localStorage (cart, wishlist, orders persist across sessions) |
| Deploy | Netlify / Vercel (zero config) |

---

## 🧪 Test Coupon Codes
| Code | Discount |
|------|---------|
| `ADDA94` | 10% off |
| `SAVE20` | 20% off |
| `WELCOME15` | 15% off |
| `FIRST50` | 50% off |

---

## 📱 Responsive
- ✅ Desktop (1200px+)
- ✅ Tablet (768px–1199px)
- ✅ Mobile (320px–767px)

---

*Built with ❤️ in India — Adda94, 2026*
