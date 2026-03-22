# smart-farm

**A simple, beautiful, offline-first farm management dashboard**

FarmFlow is a lightweight, browser-based farm management tool built with HTML, Tailwind CSS, vanilla JavaScript, and localStorage.  
It helps small to medium-scale farmers track crops, animals, finances, inventory, incidents, and daily operations — without needing a server, login, or internet after the first load.

![FarmFlow Dashboard Preview](https://via.placeholder.com/1280x720/166534/ffffff?text=FarmFlow+Dashboard+Preview)
*(Add your own screenshot here later)*

## ✨ Features

- **Dashboard**  
  Live weather (via free Open-Meteo API), simulated market prices, daily expenses & budget overview

- **Finance**  
  Income & expense logging, category breakdown, net profit/loss calculation, expense distribution chart

- **Crops & Animals**  
  Field/crop cycle tracking, planting & expected harvest dates, livestock/animal records (ID, count, notes)

- **Incidents**  
  Pest, disease & outbreak log with action taken and result rating

- **Inventory & Inputs**  
  Stock level tracking (with low-stock warnings), input price history graphs

- **Fully responsive** — mobile-friendly layout with hamburger menu  
- **100% offline after load** — all data saved in your browser  
- **No backend / No database / No login** — perfect for personal use

## 🖥️ Screenshots

(Add 4–6 screenshots here later — dashboard, finance, crops/animals, inventory)

## Tech Stack

- HTML5  
- Tailwind CSS (via CDN)  
- Vanilla JavaScript (no frameworks)  
- Chart.js (for charts)  
- Font Awesome (icons)  
- Open-Meteo (free weather API)

## 🚀 Quick Start

1. **Download** or clone the repository

   ```bash
   git clone https://github.com/yourusername/farmflow.git

   or just download the ZIP.Open any page in your browserStart with index.html or 1-home.html  
All navigation links work between pages

Use it — add records, expenses, animals, etc.
Data is automatically saved in your browser (localStorage).

No installation. No account. No internet required after first load. Project Structure

farmflow/
├── index.html          # optional landing / home page
├── 1-home.html         # main dashboard
├── 2-finance.html      # income, expenses, profit
├── 3-stock.html # crops, fields, livestock records
├── 4-incidents.html    # pest/disease/outbreak log
├── 5-inventory.html    # stock levels + price tracker
└── README.md


