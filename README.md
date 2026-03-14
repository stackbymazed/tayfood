# TayFood 🍔🍕

> A premium, highly aesthetic, and fully responsive restaurant landing page application built with Next.js 14 (App Router) & React.

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Site-success?style=for-the-badge&logoColor=white)](https://tay-food-r1y9qh7z8-nayem783982s-projects.vercel.app/)
[![Next.js](https://img.shields.io/badge/Next.js-14+-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-blue?style=for-the-badge&logo=react&logoColor=white)](https://react.dev/)

## 🚀 Live Production URL

**[https://tay-food-r1y9qh7z8-nayem783982s-projects.vercel.app/](https://tay-food-r1y9qh7z8-nayem783982s-projects.vercel.app/)**

## ✨ Features

- **Premium UI/UX:** Eye-catching design with vibrant colors, hover micro-animations, and a modern aesthetic.
- **Dynamic Scroll Animations:** Utilizes `IntersectionObserver` for satisfying counting animations on the stats counter.
- **Custom Vanilla CSS Engine:** Designed without standard utility frameworks for maximum stylistic control and uniqueness.
- **Fully Responsive Structure:** Mobile-first approach delivering flawless layouts across all device sizes.
- **Multi-page Architecture (App Router):** Fast, SEO-optimized routing including Home, About, Menu, Service, and Contact pages.
- **Component-Driven:** Modular code consisting of reusable headers, footers, and animated stat counters.
- **Lucide Icon Integration:** Clean and beautiful SVG iconography using `lucide-react`.

## 🛠️ Tech Stack

- **Framework:** Next.js (App Router)
- **Library:** React 
- **Styling:** Custom Vanilla CSS (Variables, Flexbox, CSS Grid)
- **Icons:** Lucide React
- **Deployment:** Vercel

## 📂 Project Structure

```text
src/
├── app/
│   ├── layout.tsx         # Global layout and metadata
│   ├── page.tsx           # Home landing page 
│   ├── globals.css        # Core design system and CSS variables
│   ├── about/             # About us page
│   ├── contact/           # Contact form and info
│   ├── menu/              # Detailed food menu
│   └── service/           # Service details
├── components/
│   ├── Header.tsx         # Reusable sticky navigation bar
│   ├── Footer.tsx         # Reusable multi-column footer
│   └── Counter.tsx        # IntersectionObserver based stat counter
public/
└── images/                # Generated premium food photography & assets
```

## 🏁 Getting Started

To run the project locally, run these commands in your terminal:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/stackbymazed/tayfood.git
   cd tayfood
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open in Browser:**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🤝 Contribution
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/stackbymazed/tayfood/issues).

---
*Architected and developed with ❤️ for the finest digital dining experience.*
