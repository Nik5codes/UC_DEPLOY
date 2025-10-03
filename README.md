Urban Cocoa


Overview

Urban Cocoa is a modern web application developed using React (TypeScript + Vite). It provides a scalable, modular, and production-ready structure with reusable UI components, an admin dashboard, and e-commerce features such as product pages, shopping cart, and orders.

The project is designed with both customer-facing features (browsing products, cart, login) and an admin panel (dashboard, products, orders, retailers, settings) for complete business management.

Features

User-Facing Features
Home Page with hero section, featured products, and call-to-action.
Product listing and detailed product pages.
Shopping cart functionality.
User login page.
Responsive design with reusable components.

Admin Features

Admin Dashboard with sidebar navigation.
Manage products, orders, retailers, and settings.
Secure and structured layout for admin operations.

UI Components

A wide collection of reusable UI elements such as buttons, dialogs, forms, navigation menus, tooltips, sliders, charts, and more.
Custom ProductCard component for product rendering.
Fallback image handling with ImageWithFallback.

Tech Stack

Frontend Framework: React (with TypeScript)
Build Tool: Vite
Styling: Tailwind CSS (with global styles in globals.css)
UI Components: Custom components inside src/components/ui
State Management: React hooks and context (extendable for Redux/Zustand if required)
Admin Panel: Custom-built pages for dashboard, products, orders, retailers, and settings


Project Structure
UrbanCocoa
├── dist/                     # Production build output
│   ├── assets/
│   │   ├── index.css
│   │   ├── index.js
│   │   └── index.html
│
├── src/                      # Source code
│   ├── components/           # Reusable and page-specific components
│   │   ├── figma/
│   │   │   └── ImageWithFallback.tsx
│   │   └── ui/               # Reusable UI components (accordion, button, card, etc.)
│   │
│   ├── styles/
│   │   └── globals.css
│   │
│   ├── guidelines/
│   │   └── Guidelines.md
│   │
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.html
│   ├── AdminDashboard.tsx
│   ├── AdminOrders.tsx
│   ├── AdminProducts.tsx
│   ├── AdminRetailers.tsx
│   ├── AdminSettings.tsx
│   ├── AdminSidebar.tsx
│   ├── CallToAction.tsx
│   ├── CartPage.tsx
│   ├── FeaturedProducts.tsx
│   ├── Header.tsx
│   ├── HeroSection.tsx
│   ├── HomePage.tsx
│   ├── LoginPage.tsx
│   ├── OrdersPage.tsx
│   ├── ProductCard.tsx
│   ├── ProductsPage.tsx
│   └── ProductPage.tsx
│
├── package.json
├── package-lock.json
├── tsconfig.json
├── vite.config.ts
├── README.md

Installation

Clone the repository:

git clone https://github.com/your-username/UrbanCocoa.git


Navigate to the project directory:

cd UrbanCocoa


Install dependencies:

npm install


Start the development server:

npm run dev


Build for production:

npm run build


Preview the production build:

npm run preview


Scripts

npm run dev – Start development server

npm run build – Build production bundle

npm run preview – Preview production build locally

npm run lint – Run linter (if configured)


Contributing

Contributions are welcome. Please fork the repository, create a feature branch, and submit a pull request. Ensure code follows the existing structure and conventions.