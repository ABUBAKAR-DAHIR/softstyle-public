# SoftStyle

<p align="center">
  <img src="Logo.svg" alt="SoftStyle Logo" width="300"/>
</p>

A modern fullstack e-commerce platform built with **Next.js** for discovering, browsing, and purchasing fashion products with a smooth and responsive user experience.

**🌐LIVE DEMO**: [softyle](http://softstyle-ruby.vercel.app)

## Status

This project is currently in active development.

## Note

This project is a private repo. This repo is there to only demonstrate the application.

## Vision

SoftStyle aims to become a complete e-commerce solution with:

- Product catalog and category browsing
- Search and filtering
- Shopping cart and wishlist
- Secure authentication
- Checkout and order management
- Admin dashboard for products, users, and orders

## Tech Stack

- **Frontend:** Next.js, React, TypeScript, Tailwind CSS
- **UI/UX:** Responsive components, dark/light theme support
- **Backend (planned):** Next.js API routes / full backend services
- **Database (planned):** PostgreSQL and Neon
- **Auth (planned):** BetterAuth
- **Payments (planned):** Stripe integration, UPI integration

## 📂 Project Structure
```text
softstyle/
│
├── .next/                          # Next.js build output (auto-generated)
│
├── app/                            # App Router directory
│   ├── favicon.ico
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
│
├── components/                     # Reusable UI & page sections
│   │
│   ├── ui/                         # shadcn UI components
│   │   └── button.tsx
│   │
│   ├── BestSeller.tsx
│   ├── CategList.tsx
│   ├── Cateogries.tsx
│   ├── CountrySelector.tsx
│   ├── CustomInput.tsx
│   ├── Footer.tsx
│   ├── FooterInput.tsx
│   ├── Header.tsx
│   ├── Hero.tsx
│   ├── Lister.tsx
│   ├── MensCollection.tsx
│   ├── Navbar.tsx
│   ├── NewArrival.tsx
│   ├── Plaster.tsx
│   ├── ProductItem.tsx
│   ├── PromoProductItem.tsx
│   ├── PromoProducts.tsx
│   ├── SpecialOffers.tsx
│   ├── ThemeProvider.tsx
│   └── TopRated.tsx
│
├── lib/
│   └── utils.ts                    # Utility helper functions
│
├── public/
│   └── home/
│       │
│       ├── navbar/
│       │   ├── cart.svg
│       │   ├── logo.svg
│       │   ├── love.svg
│       │   └── user.svg
│       │
│       ├── hero/
│       │   ├── 247.svg
│       │   ├── angle.svg
│       │   ├── bus.svg
│       │   ├── dollar.svg
│       │   ├── eid.svg
│       │   ├── family.svg
│       │   ├── festival.svg
│       │   ├── hero.png
│       │   ├── home-textile.svg
│       │   ├── kids.svg
│       │   ├── lingerie.svg
│       │   ├── men-fashion.svg
│       │   ├── others.svg
│       │   ├── sports.svg
│       │   ├── wallet.svg
│       │   ├── wedding.svg
│       │   └── women-fashion.svg
│       │
│       ├── category/
│       │   ├── decor.png
│       │   ├── eid.png
│       │   ├── festival.png
│       │   ├── kid.png
│       │   ├── men.png
│       │   ├── sports.png
│       │   ├── wedding.png
│       │   └── women.png
│       │
│       ├── new-arrivals/
│       │   ├── polo.png
│       │   ├── polo2.png
│       │   ├── polo3.png
│       │   ├── polo4.png
│       │   └── star.svg
│       │
│       ├── mens-collection/
│       │   └── bg.png
│       │
│       ├── promo-products/
│       │   └── bg.svg
│       │
│       └── footer/
│           ├── appstore.png
│           ├── facebook.svg
│           ├── instagram.svg
│           ├── linkedin.svg
│           ├── playstore.png
│           ├── tiktok.svg
│           ├── youtube.svg
│           └── logos/
│
├── .gitignore
├── components.json
├── eslint.config.mjs
├── next-env.d.ts
├── next.config.ts
├── package.json
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
├── postcss.config.mjs
├── tsconfig.json
└── README.md
```


## Getting Started

1. **Clone the project**
   ```bash
   git clone https://github.com/ABUBAKAR-DAHIR/softstyle.git
   cd softstyle
   ```
2. **Install dependencies**
   ```bash
   pnpm install
   pnpm dev
   ```
3. **Open the project in localhost**
   open http://localhost:3000 in your browser

## Scripts
- pnpm dev - Start development server
- pnpm build - Build for production
- pnpm start - Start production server
- pnpm lint - Run ESLint

## 👤 Author

Built as part of **[Graphicshaala](https://graphicshaala.com) Internship**.

## 📄 License

This project is proprietary!
