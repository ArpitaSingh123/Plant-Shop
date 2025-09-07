# 🌱 Plant Shop - React + Redux Project

This is a simple e-commerce style web application built using **React**, **Redux Toolkit**, and **React Router**.  
It was created as part of the final assignment project.

---

## 📌 Features

### Landing Page
- Displays company name, background image, and a brief introduction.
- Includes a **Get Started** button that links to the Product Listing page.

### Product Listing Page
- Showcases **6 unique houseplants** with thumbnail, name, and price.
- Plants are grouped into **3 categories**.
- Each plant has an **Add to Cart** button with the following behavior:
  - Increases cart count.
  - Disables button after adding.
  - Adds plant to shopping cart.

### Header
- Visible on both Product Listing and Shopping Cart pages.
- Contains navigation links.
- Displays a shopping cart icon with the current **number of items** in the cart.

### Shopping Cart Page
- Displays all selected plants with **thumbnail, name, unit price, and quantity**.
- Shows **total number of plants** and **total cost**.
- Includes **increase, decrease, and delete buttons** for each plant.
- **Checkout button** (currently displays "Coming Soon").
- **Continue Shopping button** links back to product listing page.

---

## 🛠️ Tech Stack
- **React 18**
- **Redux Toolkit**
- **React Router DOM**

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd plant-shop
