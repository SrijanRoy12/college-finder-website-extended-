# 🎓 College Finder – Extended

A modern web app built with **Next.js**, **TypeScript**, and **TailwindCSS**, designed to help students **find top colleges within a minute**. Featuring reusable UI components, theme toggle support, and tailored search capabilities.

---

##  Features
- ⏱ Quick college recommendations based on filters like stream, location, budget
- 🎯 Responsive and user-friendly interface
- 🌙 Light and dark mode via theme toggle
- ♻️ Modular components (Header, Footer, ThemeToggle) for scalability

---

##  Tech Stack
- **Framework:** Next.js (React + TypeScript)  
- **Styling:** TailwindCSS + PostCSS  
- **Configurations:** ESLint, TypeScript (tsconfig), Tailwind, PostCSS

---

##  Getting Started

### Prerequisites
- Node.js (v16+)
- npm or yarn

### Setup
```bash
git clone https://github.com/SrijanRoy12/college-finder-website-extended-.git
cd college-finder-website-extended-
npm install      # or `yarn install`
npm run dev      # or `yarn dev`
Then open http://localhost:3000 in your browser.

Project Structure
lua
Copy code
college-finder-website-extended-/
│
├── public/                   
├── src/
│   ├── components/
│   │   ├── Header.tsx
│   │   ├── Footer.tsx
│   │   ├── ThemeToggle.tsx
│   │   └── ThemeProvider.tsx
│   ├── pages/               # Next.js pages
│   └── styles/              # TailwindCSS or global styles
├── .gitignore
├── next.config.js
├── tsconfig.json
├── tailwind.config.js
├── postcss.config.js
├── package.json
└── README.md
