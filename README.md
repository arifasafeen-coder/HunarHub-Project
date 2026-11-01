# HunarHub – Digital Marketplace for Local Micro-Entrepreneurs

A responsive React + Vite academic project prototype. It demonstrates a local marketplace for customers, entrepreneurs and administrators.

## Features
- Customer marketplace: search and filter entrepreneur profiles by skill category, location and starting price.
- Entrepreneur profiles: submit a profile for admin approval.
- Service requests: customers submit requests; entrepreneur dashboard can accept, reject or complete them.
- Handmade products: browse products, add items to cart and place demo orders.
- My Activity: view requests and orders stored in the current browser.
- Admin dashboard: approve/reject entrepreneur profiles, monitor requests and orders, and view basic analytics.
- Customer support form and customer reviews.
- Responsive layout for desktop and mobile.

## Run in VS Code (Windows)
1. Install Node.js LTS from https://nodejs.org/ if it is not installed.
2. Extract this ZIP file.
3. Open VS Code → File → Open Folder → select `HunarHub_Complete_Project`.
4. Open Terminal → New Terminal.
5. Run `npm install`.
6. Run `npm run dev`.
7. Open the local URL shown in the terminal (usually `http://localhost:5173`).

## Build for deployment
Run:
```bash
npm run build
```
Vite creates the production build in the `dist` folder. For Vercel, import the project repository and use build command `npm run build` and output directory `dist`.

## Important prototype limitations
This version uses browser LocalStorage and sample demonstration data. It does not include a real server, shared database, secure login, payment gateway, SMS/email notifications, or production-grade access control. Data is saved only in the browser where it was entered. The Admin and Entrepreneur views are demonstration interfaces, not secure role-protected accounts. Replace sample records and add a backend/database and authentication before real-world use.

## Project structure
- `src/App.jsx` – marketplace, forms, customer activity, entrepreneur dashboard and admin dashboard.
- `src/App.css` – responsive styling.
- `src/index.css` – global styling.
- `docs/PRD_and_Technical_Documentation.md` – project requirements and technical documentation.
