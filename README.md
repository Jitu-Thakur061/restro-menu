# 🍽️ Flavour House — Premium Restaurant Digital Menu Website

A modern, responsive, and aesthetic restaurant digital menu website built strictly using semantic **HTML5** and modern **CSS3**. Designed with a warm dark-brown and cream visual identity, elegant serif typography, subtle drop-shadows, and golden accents suitable for real-world restaurant presentation.

**Repository Link:** [https://github.com/Jitu-Thakur061/restro-menu.git](https://github.com/Jitu-Thakur061/restro-menu.git)  
**Live Demo (GitHub Pages):** [https://jitu-thakur061.github.io/restro-menu/](https://jitu-thakur061.github.io/restro-menu/) *(Live once deployed via GitHub Pages)*

---

## 📸 Website Preview

<!-- Replace the placeholder path below with your actual screenshot after capturing it -->
```markdown
![Flavour House Preview](assets/screenshot.png)
```
> *Tip for adding your screenshot:* Capture a screenshot of the running website in your browser, create an `assets/` folder, save the screenshot as `assets/screenshot.png`, and update the preview image above.

---

## ✨ Key Features

- **Warm & Elegant Design Identity:**
  - Rich dark-brown header, hero, and footer surfaces (`#241913`).
  - Warm cream and light-beige body backgrounds (`#faf5ed`).
  - Terracotta orange and warm gold accents (`#c8632d` & `#e5a74e`) for prices, ratings, and call-to-action buttons.
  - Editorial serif headings powered by *Playfair Display* and clean body typography with *DM Sans*.

- **Sticky Navigation Header:**
  - Working smooth-scroll internal anchors linking to all primary sections.
  - Highlighting restaurant identity with an illuminated brand logo.
  - Prominent "Explore Menu" call-to-action button.

- **Hero Showcase:**
  - Full-width hero banner with dark gradient overlays ensuring high text readability.
  - Compelling tagline, introduction, rating badges, and fast-action buttons.

- **Interactive Food Categories:**
  - 6 category cards: Starters, Main Course, Pizza & Pasta, Burgers, Desserts, and Beverages.
  - Hover zoom animations and smooth elevation transitions.

- **Complete 18-Item Digital Menu with Indian Rupee (₹) Pricing:**
  - 6 dedicated sections with 3 realistic dishes per category.
  - Standard Indian vegetarian (green dot) and non-vegetarian (red dot) indicators.
  - Appetizing descriptions, tags (`Bestseller`, `Chef's Pick`, `House Signature`, etc.), and prices.

- **Chef's Signature Specials:**
  - Dedicated luxury showcase cards highlighting signature recipes (Royal Handi Biryani, Mughlai Butter Chicken, Truffle Pizza, Sizzling Brownie).
  - Callout reservation banner.

- **About Us & Storytelling:**
  - Clean two-column layout highlighting farm-to-table sourcing, master chefs, and warm hospitality.

- **Why Choose Us:**
  - 6 distinct feature benefit cards (Fresh Ingredients, Expert Chefs, Uncompromising Quality, Comfortable Dining, Authentic Taste, Friendly Hospitality) using pure CSS and Unicode symbols without heavyweight icon dependencies.

- **Contact & Visit Information:**
  - Clear placeholder cards for address, opening hours, phone numbers, and email.
  - Fully styled accessible contact form with name, email, subject, and message inputs.
  - Static form disclaimer clearly noting that submissions require a backend or third-party service (e.g., Formspree).

- **Multi-Column Restaurant Footer:**
  - Brand description, quick navigation links, menu highlights, operating hours, copyright, and a smooth back-to-top button.

- **Mobile First & Fully Responsive:**
  - Tested and optimized across 320px, 375px, 768px, 1024px, and 1440px displays.
  - Zero horizontal overflow.
  - Accessibility-first with `:focus-visible` outlines and `@media (prefers-reduced-motion)` support.

---

## 🛠️ Technologies Used

- **HTML5:** Semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<form>`, `<footer>`), descriptive `alt` tags, accessible form labels, and meta viewport tags.
- **CSS3:** Modern CSS Custom Properties (variables), Flexbox, CSS Grid layouts, clamp functions for fluid typography, custom transitions, and media queries.
- **No external frameworks or libraries:** No JavaScript, React, Bootstrap, Tailwind, or jQuery used.

---

## 📁 Project File Structure

```text
restro-menu/
├── index.html       # Primary semantic HTML5 structure and markup
├── style.css        # Complete CSS3 styles, variables, grid layouts, and responsiveness
└── README.md        # Comprehensive project documentation
```

---

## 🚀 How to Run the Website Locally

Since this is a static website built with pure HTML5 and CSS3, no build steps, Node.js, or package managers are required.

### Method 1: Direct File Opening
1. Download or clone this repository to your local computer.
2. Open the project folder.
3. Double-click `index.html` to open it in any web browser (Google Chrome, Microsoft Edge, Firefox, Brave, Safari).

### Method 2: Using VS Code Live Server (Recommended)
1. Open Visual Studio Code.
2. Click **File > Open Folder...** and select the `Restaurant-Digital-Menu` (or `restro-menu`) folder.
3. Install the **Live Server** extension by Ritwick Dey (if not already installed).
4. Right-click on `index.html` in the file explorer.
5. Click **Open with Live Server**. The site will open automatically at `http://127.0.0.1:5500`.

---

## 🌐 How to Publish with GitHub Pages

You can host this website completely free using GitHub Pages:

1. Open your repository on GitHub: [https://github.com/Jitu-Thakur061/restro-menu](https://github.com/Jitu-Thakur061/restro-menu)
2. Click on the **Settings** tab near the top right of the repository page.
3. In the left navigation sidebar, click on **Pages** (under the "Code and automation" section).
4. Under **Build and deployment**:
   - **Source:** Select `Deploy from a branch`.
   - **Branch:** Select `main` (or your active default branch) and set the folder to `/ (root)`.
5. Click **Save**.
6. Wait 1 to 2 minutes for GitHub Actions to build and deploy your site.
7. Refresh the GitHub Pages settings page. A banner will appear at the top:
   > *Your site is live at https://jitu-thakur061.github.io/restro-menu/*
8. Click the link to view your live deployed restaurant menu website!

---

## 📋 Quality & Testing Checklist

- [x] Semantic HTML5 layout with proper heading hierarchy (`h1` through `h4`).
- [x] Zero JavaScript dependency.
- [x] Linked external `style.css` stylesheet without inline styles.
- [x] Fully functioning internal navigation anchors (`#home`, `#categories`, `#menu`, `#specials`, `#about`, `#why-us`, `#contact`).
- [x] Responsive layout across mobile, tablet, and desktop viewports.
- [x] All images configured with meaningful `alt` descriptions and lazy loading.
- [x] Contact form includes descriptive labels, inputs, and a static form notice.
- [x] Accessible keyboard navigation with `:focus-visible` indicators.

---

## 📄 License & Attribution

This project is created for educational, portfolio, and demonstration purposes. Food photography provided courtesy of [Unsplash](https://unsplash.com).
