# Noir Collective — Hair Care Rooted in Truth

![Noir Collective](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Deployed-Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)

**Live Site →** [https://noir-collective.tiiny.site](https://noir-collective.tiiny.site)

---

## Overview

Noir Collective is a premium e-commerce website built for a natural hair care brand rooted in Black identity and botanical science. The project spans brand strategy, UI/UX design, and front-end development — covering three distinct product ranges, a multi-step checkout flow, and a founder story that anchors the brand in cultural truth.

> *"Your crown has always grown."*

---

## Features

- **Three Range Experiences** — each with its own visual identity, palette and tone
  - The Crown (Women's Range)
  - The Sovereign (Men's Range)
  - Little Crowns (Kids' Range)
- **Tabbed Navigation** — seamless switching between ranges
- **Product Cards** — with hover interactions and Add to Cart functionality
- **Live Cart** — running total, item count, remove items
- **Multi-Step Checkout** — Shipping → Payment → Order Confirmation
- **Founder Story Section** — cultural narrative and brand origin
- **Responsive Design** — mobile, tablet and desktop
- **Smooth Scroll Animations** — fade-in-up on scroll via IntersectionObserver
- **Sticky Nav** — with scroll-aware background transition
- **Self-Contained** — all images embedded as base64, zero external dependencies

---

## Product Ranges

### The Crown — Women's Range
| Product | Price |
|---|---|
| Crown Scalp Tonic | R150 |
| Crown Vitality Oil | R190 |
| Crown Seal | R190 |
| The Complete Crown Ritual (Bundle) | R500 |

### The Sovereign — Men's Range
| Product | Price |
|---|---|
| Reign Scalp Elixir | R180 |
| Sovereign Growth Oil | R220 |
| Obsidian Edge Butter | R160 |
| Patriarch Beard Oil | R200 |
| Crown Wrap Serum | R175 |
| The Sovereign Set (Bundle) | R650 |

### Little Crowns — Kids' Range
| Product | Price |
|---|---|
| Tender Roots Scalp Milk | R135 |
| Petal Soft Detangling Spray | R120 |
| Bloom Curl Custard | R145 |
| Sunshine Growth Serum | R150 |
| Cloud Nine Leave-In | R130 |
| Little Crowns Starter Kit (Bundle) | R420 |
| Crown Comb Set | R85 |
| Satin Hair Bands | R55 |
| Crown Clips Set | R70 |
| Satin Sleep Bonnet | R90 |

---

## Colour Palette

| Range | Background | Accent | Gold |
|---|---|---|---|
| Women — The Crown | `#FFFFFF` | `#6B1A2A` Bordeaux | `#C4A882` |
| Men — The Sovereign | `#111418` Onyx | `#B69057` Antique Gold | `#2C3540` Steel |
| Kids — Little Crowns | `#FDF8F5` Cream | `#C2785A` Terracotta | `#F0C8B0` Blush |

---

## Typography

| Role | Font | Weight |
|---|---|---|
| Display / Headings | Cormorant Garamond | 300, 400, 500, 600 |
| Body / UI | Jost | 200, 300, 400, 500 |

Both fonts served via Google Fonts.

---

## Tech Stack

| Tool | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling, animations, responsive layout |
| Vanilla JavaScript | Cart logic, checkout flow, scroll behaviour |
| Google Fonts | Typography |
| Claude AI (Anthropic) | Design direction, brand strategy, copywriting, development |
| Netlify / Tiiny.host | Deployment & hosting |

---

## File Structure

```
noir-collective/
│
├── index.html          # Complete self-contained site (all assets embedded)
├── README.md           # This file
└── assets/             # (optional) extracted images if refactored
```

> The current build is intentionally a single self-contained HTML file — all images are embedded as base64 data URIs, requiring no server, build tool or package manager.

---

## Getting Started

### View Locally

No build steps required. Simply open the file in any browser:

```bash
git clone https://github.com/tweety-KM/noir-collective.git
cd noir-collective
open index.html
```

Or double-click `index.html` — it runs entirely in the browser.

### Deploy to Netlify

1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag and drop `index.html`
3. Netlify generates a live public link instantly
4. Optionally rename the site under **Site Settings → Change site name**

---

## Roadmap

- [ ] CMS integration (Framer CMS or Sanity) for product management
- [ ] Framer export and rebuild as component-based site
- [ ] Backend checkout integration (Stripe or PayFast for ZA)
- [ ] WhatsApp order flow integration
- [ ] Blog / Hair Journal section
- [ ] Loyalty programme UI
- [ ] Multi-currency support (ZAR / USD / GBP)

---

## Export Ready

This project is structured for export to:

- **Figma** — via the HTML to Figma plugin by Builder.io
- **Framer** — via Figma import or direct HTML embed

---

## Brand Story

Noir Collective was born from a simple, painful truth — that an entire generation of Black women grew up believing their hair didn't grow. Not because it didn't. But because everything around them — the television, the classroom, the products on the shelf — was designed for someone else's texture.

It took a visit to a grandmother's kitchen, and shelves lined with natural oils and botanical blends she'd made herself, to understand that Black hair was never broken. It was simply never properly accommodated.

Noir Collective exists to correct that — one ritual at a time.

---

## License

This project is for portfolio and demonstration purposes.
All brand assets, product names, copy and design are original work.

---

## Contact

Built with intention by **[Koketso Matobako]**

