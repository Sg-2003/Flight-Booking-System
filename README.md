# ✈️ Flivan — Flight Booking Landing Page

A modern, responsive airline booking landing page for **Flivan Airlines**, built with pure HTML and CSS. Designed to deliver a premium travel experience at a glance.

---

## 🚀 Live Preview

Open `index.html` directly in your browser — no build tools or server required.

---

## 📸 Features

- **Sticky Navigation Bar** — Logo, nav links, and a contact CTA button
- **Hero Header** — Full-width banner image with a bold headline
- **Flight Booking Form** — Supports Economy, Business, and First Class selection with fields for:
  - Destination / Location
  - Number of Travellers
  - Departure Date
  - Return Date
- **Travel Support Section** — Highlights destination requirements, travel insurance, and trip planning info
- **Memories Section** — "Book & Relax", Smart Checklist, and Save More feature cards
- **Lounge Section** — Showcases the Unaccompanied Minor Lounge with experience highlights
- **Best Travellers Section** — Monthly featured travellers with destinations
- **Newsletter Subscription** — Email subscribe form
- **Footer** — Brand info, navigation links, contact links, social media icons, and copyright

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic page structure |
| **CSS3** | Layout, animations, responsive design |
| **Google Fonts — Poppins** | Typography |
| **Remix Icons** | UI icons (via CDN) |

---

## 📁 Project Structure

```
Flight-booking/
├── index.html      # Main HTML page
├── style.css       # All styles, variables, and responsive breakpoints
└── README.md       # Project documentation
```

---

## 🎨 Design System

### Color Palette

| Token | Value | Usage |
|---|---|---|
| `--primary-color` | `#3d5cb8` | Buttons, active states, footer |
| `--primary-color-dark` | `#334c99` | Button hover |
| `--text-dark` | `#0f172a` | Headings, labels |
| `--text-light` | `#64748b` | Body text, hints |
| `--extra-light` | `#f1f5f9` | Section backgrounds, borders |
| `--white` | `#ffffff` | Card backgrounds, text on dark |

### Typography

- **Font Family**: [Poppins](https://fonts.google.com/specimen/Poppins) (weights: 100–900)
- **Section Headers**: `2.5rem – 3rem`, `font-weight: 600`
- **Body Text**: `1rem`, `font-weight: 400–500`

---

## 📱 Responsive Breakpoints

| Breakpoint | Changes |
|---|---|
| `< 1200px` | Overflow hidden on header, plan, and lounge containers |
| `< 900px` | Nav button hidden; booking form goes to 2 columns; memories grid to 2 columns; travellers grid to 2 columns |
| `< 600px` | Nav links hidden; booking form goes to 1 column; all grids collapse to 1 column; footer stacks vertically |

---

## ⚙️ Getting Started

No installation needed. Simply:

1. Clone or download this repository
2. Open `index.html` in any modern browser

```bash
# Clone the repository
git clone https://github.com/your-username/flight-booking.git

# Open in browser
start index.html      # Windows
open index.html       # macOS
xdg-open index.html   # Linux
```

---

## 🔗 External Dependencies

All dependencies are loaded via CDN — no `npm install` needed:

- **Remix Icons** `v4.3.0` — [remixicon.com](https://remixicon.com)
- **Google Fonts (Poppins)** — [fonts.google.com](https://fonts.google.com)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

Copyright © 2024 **Sg Developer** — All rights reserved.
