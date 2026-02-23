# Poshak
POSHAk – Smart Weekly Meal Planner (Offline-First PWA)

POSHAk is a simple, distraction-free, offline-first meal planning web app designed to help individuals and families plan their weekly meals efficiently — including adults and toddlers in the same view.

Built using HTML, CSS, and JavaScript, POSHAk runs entirely in the browser with localStorage support and is installable as a Progressive Web App (PWA).

✨ Why POSHAk?

Meal planning often feels overwhelming — especially when planning separately for adults and children. POSHAk solves this by:

Showing the entire weekly meal plan at once

Allowing a separate column for a 1-year-old child

Offering food suggestions/autocomplete

Generating a persistent grocery list

Working fully offline

🚀 Features
🗓 Weekly Meal Planner

View Monday–Sunday in a single screen

Multiple meal slots (Breakfast, Lunch, Snacks, Dinner)

Separate column for:

👩 Adults

👶 1-Year-Old Child

Instant save using localStorage

Resume exactly where you left off

🔍 Smart Suggestions

Autocomplete food suggestions while typing

Reuse previously entered items

Reduces repetitive typing

📖 Recipe Manager

Add custom recipes

Attach external recipe links

Search functionality

Clean list + detail view UX

🛒 Grocery List Generator

Auto-compiles ingredients from weekly plan

Persistent storage

Easy add/remove functionality

📱 Offline-First PWA

Installable on desktop and mobile

Works without internet

Fast loading

App-like experience

🧱 Tech Stack

HTML5

CSS3

Vanilla JavaScript

localStorage

Service Worker (PWA)

Web App Manifest

No frameworks. No dependencies. Lightweight and fast.

📂 Project Structure
POSHAk/
│
├── index.html          # Main meal planner
├── recipes.html        # Recipe manager
├── grocery.html        # Grocery list
│
├── css/
│   └── styles.css
│
├── js/
│   ├── app.js
│   ├── storage.js
│   ├── autocomplete.js
│   └── grocery.js
│
├── manifest.json
├── service-worker.js
└── README.md
💾 How Data is Stored

POSHAk uses browser localStorage to store:

Weekly meal plans

Recipes

Grocery lists

User preferences

No backend. No cloud storage. Your data stays on your device.

🛠 How to Run Locally

Clone the repository:

git clone https://github.com/your-username/poshak.git

Navigate to the folder:

cd poshak

Open index.html in your browser
OR use a local server (recommended for PWA):

npx serve .

Open in browser and install as an app.

📌 Roadmap

 Ingredient-level auto aggregation

 Nutritional insights

 Export weekly plan as PDF

 Multi-user profile support

 Cloud sync option

 Drag & drop meal planning

🎯 Product Philosophy

POSHAk is built around:

Simplicity over complexity

Visibility over hidden views

Family-first design

Offline reliability

No unnecessary features

🤝 Contributions

Currently a personal product build.

If you'd like to contribute:

Fork the repository

Create a feature branch

Submit a pull request



👩‍💻 Built By

Shabeera
Product Builder | Marketing Leader | Learning-by-Building
