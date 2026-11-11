# 🍞 Bakery Press Calculator

A Progressive Web App (PWA) for calculating dough weight and press requirements in a production bakery.

**Live app:** https://timson974.github.io/bakery-press/

---

## Features

- 🔐 Login for 3 roles: Baker, Supervisor, Admin
- 📋 10 product sections (Dinner Rolls, Baps, Muffins, Ciabatta, Focaccia, Tiger Bread, Panini, Baguettes, Tins 800g/1600g, Bloomers & Cobs)
- ⚙️ Auto-calculates number of presses and dough required (kg)
- 📱 Installable as a mobile app (PWA)
- 📶 Works offline via Service Worker

---

## Project Structure

bakery-press/
├── index.html # Main app (login + calculator)
├── manifest.json # PWA manifest
├── sw.js # Service Worker (offline support)
├── icon-192.png # App icon 192×192
└── icon-512.png # App icon 512×512


---

## Install on Phone

1. Open https://timson974.github.io/bakery-press/ in Chrome
2. Tap menu (⋮) → **"Add to Home screen"**
3. Done — opens like a native app
