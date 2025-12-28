# Essenza 👜

### Minimalist E-commerce Architecture built with Next.js & TypeScript

![Status](https://img.shields.io/badge/Status-MVP_Showcase-blue) ![Stack](https://img.shields.io/badge/Stack-Next.js_14_%7C_TypeScript-black)

![Essenza Homepage Preview](screenshot.png)

## ⚡ Overview

**Essenza** is a high-performance e-commerce platform designed for luxury retail. The goal was to build a shopping experience that feels as premium as the products it sells—fast, seamless, and aesthetically pleasing.

Built with **Next.js 14** and **TypeScript**, this project focuses on Core Web Vitals, server-side rendering for SEO, and strict structural integrity using strong data models.

*(Note: This project serves as a technical showcase of my Product Engineering skills)*

## 🛠 Tech Stack

* **Frontend:** Next.js (App Router), TypeScript, Tailwind CSS.
* **Backend:** Node.js (API Routes).
* **State:** React Context for cart management.
* **Design:** Mobile-first, responsive UI with a focus on micro-interactions.

## 🚀 Key Features

- [x] **SSR & Hydration:** Optimized for near-instant first contentful paint (FCP).
- [x] **Dynamic Catalog:** Category filtering and product routing using Next.js dynamic segments.
- [x] **Robust Data Modeling:** Strict usage of **Models** (Interfaces) for Products, Cart, and Users to ensure data consistency.
- [x] **Cart Logic:** Persistent state management with local storage synchronization.
- [x] **Responsive Design:** Fully fluid layout adapting from mobile to desktop.

## 💻 Code Structure

I followed a modular architecture to keep the codebase clean and scalable:

```bash
/src
  /components    # UI Atoms (Navbar, ProductTile)
  /app           # Next.js 14 App Router structure
  /lib           # Utils and fetch wrappers
  /models        # Data definitions and Interfaces (Product, User, Order)

```

## 🤝 Context

**Essenza** was developed as a comprehensive university project in collaboration with Carmen Noblejas. It demonstrates the ability to deliver a complete, functional product from concept to deployment.

## 📦 How to Run

1.  Clone the repository:
    ```bash
    git clone [https://github.com/pabloflow/essenza-ecommerce.git](https://github.com/pabloflow/essenza-ecommerce.git)
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Start the development server:
    ```bash
    npm run dev
    ```
    

---
*Built by [Pablo Flores](https://www.linkedin.com/in/pablo-flores-moreno-23970a366/). Crafting software with product sensibility.*