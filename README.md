# StockWise — Inventory Management Dashboard

A React + Vite portfolio project demonstrating practical frontend development skills.

## Features
- Dashboard KPIs for product count, units, inventory value and low-stock alerts
- Stock-by-category visualization and replenishment alerts
- Product inventory table with search, category and stock filters
- Add products and adjust stock quantities
- Product details drawer
- Purchase order listing and supplier directory
- Export product inventory to CSV
- JSON seed data with localStorage persistence
- Responsive desktop and mobile interface

## Tech stack
React, Vite, JavaScript, CSS and Lucide React.

## Run locally
Requires Node.js 18 or newer.

```bash
npm install
npm run dev
```

Build with `npm run build`.

## Data storage
Sample records are stored in `src/data/products.json` and `src/data/orders.json`. Browser changes are persisted in localStorage (`stockwise-products-v1`). A static frontend cannot write changes back to its JSON asset. Clear that localStorage key to restore the original product list.

## Portfolio description
**StockWise — Inventory Management Dashboard**

Built a responsive inventory management dashboard using React.js and Vite. Implemented product creation, searchable and filterable inventory, stock adjustments, low-stock alerts, category summaries, purchase order tracking, supplier views, CSV export and browser persistence using JSON seed data and localStorage.

**Skills:** React Hooks, reusable components, controlled forms, CRUD workflows, derived state, data filtering, CSV export, responsive CSS and client-side persistence.

## Project structure
```
src/
  data/products.json
  data/orders.json
  App.jsx
  main.jsx
  styles.css
```

## Future enhancements
Add tests with Vitest and React Testing Library, pagination, sorting, purchase order receiving workflows, authentication and API-backed storage.
