# BAC Calculator Maroc – Web App

BAC Calculator Maroc is a responsive single-page web application (SPA) that allows Moroccan students to:

- Calculate their BAC average (Tronc Commun, 1BAC, 2BAC)
- Compute the final 2BAC average using the official formula (CC, Examen Régional, Examen National)
- Estimate their acceptance score for CPGE, BTS, ENSA, EST, FST and custom programs
- Save their data locally (localStorage)
- Use light/dark mode with a modern Tailwind-style UI

This package includes the full front-end source code (HTML, CSS, JS) ready to deploy on any static hosting (Vercel, Netlify, shared hosting, etc.).

---

## Features

### Core Features

- ✅ **BAC Average Calculator**
  - Supports **Tronc Commun**, **1BAC**, **2BAC**
  - Weighted average by subject coefficients
  - Add, edit, remove subjects dynamically

- ✅ **Final 2BAC Average (Official Formula)**
  - Inputs for:
    - Contrôle Continu (CC)
    - Examen Régional (ER)
    - Examen National (EN)
  - Adjustable weights (default: 25% / 25% / 50%)
  - Automatic calculation of final average
  - Mentions: Passable, Assez Bien, Bien, Très Bien

- ✅ **Acceptance Score Estimator**
  - Programs: **CPGE, BTS, ENSA, EST, FST, Personnalisé**
  - Uses:
    - Moyenne 2BAC
    - Moyenne 1BAC
    - Moyenne Tronc Commun
    - Note Examen National
    - Key subjects: Math, Physique-Chimie, SVT/Sciences de l’Ingénieur
  - Adjustable coefficients per program
  - Visual chance indicator (Faible, Moyenne, Élevée)

- ✅ **UX & UI**
  - Fully responsive (desktop, tablet, mobile)
  - Light / Dark mode toggle
  - Tailwind-like design via CDN
  - Sticky header, sidebar stats, tabs navigation

- ✅ **Persistence & Privacy**
  - Saves all user inputs locally (localStorage)
  - No backend, no database required
  - Easy to integrate AdSense: predefined ad placeholders

---

## Technologies

- Pure **HTML5**
- **Tailwind CSS via CDN** (`@tailwindcss/browser@4`)
- **Vanilla JavaScript** (no build step, no frameworks)
- Uses localStorage for client-side persistence

---

## File Structure

```text
bac-calculator-maroc/
├── index.html          # Main application (all UI + logic)
├── README.md           # This file
├── documentation.html  # Formatted documentation for buyers
└── CHANGELOG.txt       # Version history
