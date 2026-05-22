# NOIR Fine Dining — Complete Website

## 🖤 Overview
Premium luxury restaurant website with dark gold aesthetics, cinematic animations, floating 3D food cards, full menu system, reservation form, AI concierge chatbot, and cart ordering.

## 📁 Project Structure
```
noir-restaurant/
├── noir-complete.html      ← SINGLE FILE (open this in any browser)
├── index.html              ← Multi-file version entry point
├── README.md
├── css/
│   ├── style.css           ← Main styles, layout, components
│   ├── animations.css      ← Keyframes & reveal animations
│   ├── components.css      ← Reusable UI components
│   └── responsive.css      ← Mobile / tablet breakpoints
└── js/
    ├── data.js             ← All dishes, menu, reviews, gallery data
    ├── cart.js             ← Cart sidebar, add/remove, totals
    ├── animations.js       ← Cursor, particles, parallax, tilt, counters
    ├── chatbot.js          ← AI concierge chatbot logic
    └── main.js             ← Section rendering, reservation, gallery
```

## 🚀 How to Open
**Easiest:** Double-click `noir-complete.html` — works offline, no server needed.

**Multi-file version:** Serve `index.html` via any local server:
```bash
# Python
python -m http.server 3000

# Node.js
npx serve .

# VS Code
Live Server extension → Open with Live Server
```

## ✨ Features
| Feature | Details |
|---|---|
| Hero | Fullscreen with floating food cards, particle canvas, parallax |
| Featured Dishes | 6 signature dishes with 3D tilt hover + add to cart |
| Full Menu | 6 categories, 24 items, animated tab filter, add to cart |
| Chef Section | Portrait, bio, animated stat counters |
| Private Dining | 3 room types with details |
| Reservation | Validated form with confirmation flow |
| Reviews | Infinite auto-scroll with 8 testimonials |
| Gallery | 12-item masonry grid with lightbox |
| Cart Sidebar | Full cart with quantity control + service charge |
| AI Chatbot | Keyword-based concierge with quick replies |
| Cursor | Custom gold cursor with smooth ring follow |
| Particles | Canvas-based gold dust particles |
| Scroll Reveal | IntersectionObserver-powered entrance animations |
| Counters | Animated number counters for chef stats |
| Responsive | Mobile-first, works on all screen sizes |

## 🎨 Design System
- **Primary:** `#c9a84c` (Gold)
- **Background:** `#080808` (Near Black)
- **Text:** `#e8e0d0` (Warm White)
- **Fonts:** Cormorant Garamond (headings) + Montserrat (body)

## 🛠 Customisation
- Edit dish data in `js/data.js`
- Change restaurant name/address in `index.html` or `noir-complete.html`
- Swap colours in `css/style.css` → `:root` variables
- Add/remove menu items in `MENU_ITEMS` array in `js/data.js`

## 📞 Contact Details (change these)
- Phone: +94 11 234 5678
- Email: reservations@noir.lk
- Address: 42 Galle Face Terrace, Colombo 03
