# Swiggy Landing Page Clone

> Landing website built using **only HTML5 and CSS3** — 0 lines of JavaScript, no Bootstrap/Tailwind.

**Submitted by:** Aarti Rani
**Email:** aartirani2972004@gmail.com
**Phone:** +91 92585 35878

A responsive clone of the Swiggy (https://www.swiggy.com/) homepage built with **HTML5 and CSS3 only** — no JavaScript, no CSS frameworks.

## How to run
Open `index.html` in any modern browser (Chrome, Edge, Firefox). No installation needed.

## Folder structure
```
swiggy-clone/
├── index.html          # Page structure (semantic HTML5)
├── style.css           # All styling + media queries
├── README.md
├── assets/
│   ├── logo.svg, logo-orange.svg, favicon.svg
│   ├── hero-left.svg, hero-right.svg      # Banner illustrations
│   ├── service-*.svg                      # Food Delivery / Instamart / Dineout cards
│   ├── food/        # 12 food category images
│   ├── instamart/   # 8 grocery category images
│   └── icons/       # Social media icons
└── screenshots/
    ├── desktop-view.png, desktop-top.png  # 1440px
    ├── tablet-view.png                    # 820px
    ├── mobile-view.png, mobile-1..5.png   # 390px (iPhone size)
    └── mobile-menu-open.png               # CSS-only menu opened
```

## Sections implemented
1. **Header / Navbar** – logo, Swiggy Corporate, Partner with us, Get the App, Sign in
2. **Main Banner** – orange hero, heading, delivery location input, search bar, side food illustrations
3. **Service Cards** – Food Delivery, Instamart, Dineout (heading, sub-text, offer, image, arrow button)
4. **Food Categories** – "Order our best food options": Pizza, Burger, Biryani, Cakes, North Indian, South Indian + 6 more
5. **Instamart Categories** – "Shop groceries on Instamart": Fresh Vegetables, Fresh Fruits, Dairy, Munchies, Cold Drinks, Personal Care + 2 more
6. **City Links** – cities with food delivery and grocery delivery
7. **Footer** – app download section, Company / Contact / Legal / Available in / Life at Swiggy links, social icons, copyright

## Technical highlights
- **CSS Grid** – service cards, food grid, Instamart grid, city links, footer columns
- **Flexbox** – navbar, search row, cards content, app band, footer columns
- **CSS variables** (`:root`) for colours, radius and font
- **Media queries** at 1280px, 1024px (tablet), 768px (mobile) and 480px (small phones)
- **CSS-only hamburger menu** on mobile (hidden checkbox + `:checked` selector, animated to an ✕) — no JavaScript
- **Fluid typography** with `clamp()` so headings scale smoothly between screen sizes
- Hover effects with CSS transitions
- Semantic tags: `header`, `nav`, `main`, `section`, `footer`; `alt` text on all images
- Tested: no horizontal scrolling at 1440px, 820px and 390px widths

## Responsive behaviour
| Screen  | Changes |
|---------|---------|
| Desktop | Full navbar, side illustrations, 3 cards in a row, 6-column food grid, 8-column Instamart grid |
| Tablet  | Corporate/Partner links hidden, smaller illustrations, 4-column grids, 3-column footer |
| Mobile  | Hamburger menu (CSS only), stacked search fields, horizontal service cards stacked vertically, 3-column food grid, 4-column Instamart grid, 2-column footer |

## Note
Food and grocery images are custom SVG illustrations created for this project.
