# Arpit Jindal — Video, Design & Data

Personal creative freelancer portfolio showcasing short-form video editing, visual graphic design, Excel systems, and data visualization — with a built-in pricing system and organized freelance asset library.

### 🌐 Live Portfolio → [https://arpit-jindal-01.github.io/profolio/](https://arpit-jindal-01.github.io/profolio/)

---

## About

A studio-style portfolio built around three core creative modes — **Video**, **Design**, and **Data** — demonstrating how raw footage, blank canvases, and unorganized spreadsheets are transformed into clear, engaging content, memorable visuals, and understandable systems.

---

## Services

### Video
- Short-form videos (Reels / Shorts / TikTok)
- Event promos & recap videos
- Animated captions & motion graphics
- B-roll integration & pacing
- Transitions & sound design
- Color correction & visual polish

### Design
- Social media creatives & carousel posts
- Food & beverage promotional posters
- Digital menu designs
- Brand campaign visual assets
- Print & digital marketing graphics

### Data
- Interactive Excel & Google Sheets dashboards
- Data cleaning & ETL pipelines
- Automated formulas & conditional logic
- Inventory management & CRM tracking systems
- Monthly business performance reporting

---

## Tech & Tools

### Core Development
- HTML5 / CSS3 / JavaScript (Vanilla)

### Video Editing
- Adobe Premiere Pro
- Adobe After Effects
- DaVinci Resolve
- Clipchamp / CapCut

### Visual Design
- Figma
- Canva
- Adobe Photoshop
- Adobe Illustrator

### Data Analytics
- Microsoft Excel & Pivot Tables
- Google Sheets
- Power Query & Power BI

---

## Portfolio Sections

- **Hero / Studio Introduction:** High-impact typography with mouse-interactive background grid.
- **Three Modes Showcase:** Interactive overview of Video, Design, and Data services.
- **Selected Work Gallery:** Filterable masonry portfolio with real video playback, design creative showcases, and live-rendered synthetic dashboards.
- **Chaos to Clarity:** Visual transformation breakdown showing workflow logic.
- **The Toolbox & Methodology:** Capability overview and human-guided AI acceleration workflow.
- **Interactive Solution Finder:** Dynamic query selector ("What do you have?") recommending services & filtering projects.
- **Pricing System:** Three clean service cards (Design, Excel & Data, Video) with expandable pricing modals, multi-service packages, and a custom quote CTA — all linking to the enquiry form.
- **Contact & Enquiry System:** Direct contact cards and inline project enquiry form.

---

## Contact

**Arpit Jindal**  
*Independent Creative Freelancer*

- **Email:** [jindalarpit0228@gmail.com](mailto:jindalarpit0228@gmail.com)
- **LinkedIn:** [https://www.linkedin.com/in/arpit-jindal-748264389/](https://www.linkedin.com/in/arpit-jindal-748264389/)
- **GitHub:** [https://github.com/Arpit-Jindal-01](https://github.com/Arpit-Jindal-01)

*(Freelance platform profiles on Fiverr and Upwork will be integrated once profiles are live).*

---

## Portfolio Asset Library

The `ARPiT_FREELANCE/` directory contains the organized master library for all freelance work. It is **independent from the website code** and is not deployed to the live portfolio.

```text
ARPiT_FREELANCE/
│
├── DESIGN/
│   ├── Social Media/       — Instagram posts, stories, carousels
│   ├── Posters/            — Event posters, promotional creatives
│   ├── Presentations/      — Pitch decks, slide decks
│   └── Other/              — Flyers, banners, misc design work
│
├── EXCEL/
│   ├── Dashboards/         — Interactive Excel/Sheets dashboards
│   ├── Data Cleaning/      — Data cleaning & ETL work
│   ├── Trackers/           — CRM, inventory, sales trackers
│   └── Reports/            — Business reports & performance docs
│
├── VIDEO/                  — Video editing projects
│
├── CLIENT-SAMPLES/         — Sanitized/public-safe sample deliverables
│
└── PROPOSALS/
    └── RATE-CARD.md        — Internal rate card & pricing policy
```

Each project follows a standardized folder structure:

```text
PROJECT-NAME/
├── Preview/       — Optimized image/video for web, Fiverr, Upwork, proposals
├── Source/        — Original editable files (.psd, .ai, .fig, .xlsx, etc.)
├── Final/         — Final deliverables
└── Description.md — Project metadata
```

> **Privacy:** No confidential client files, personal data, private contracts, API keys or private communications are committed to this repository.

---

## Pricing System

The portfolio includes a built-in pricing section (accessible via the `PRICING` nav link) that shows:

- **Three clean service cards** — Design (from ₹500), Excel & Data (from ₹999), Video (from ₹700)
- **Expandable pricing modals** — Full service price lists shown on demand, keeping the main page uncluttered
- **Multi-service packages** — Design+Video, Design+Data, Complete Content (all linked to custom quote)
- **Custom Quote CTA** — `GET CUSTOM QUOTE →` and `BUILD MY PACKAGE →` both lead to the enquiry form
- **Pricing disclaimer** — *"Starting prices. Final quotes depend on project scope, complexity, timeline and deliverables."*

The internal rate card including revision policy, rush fees, payment terms, and scope-change policy is in `ARPiT_FREELANCE/PROPOSALS/RATE-CARD.md`.

---

## Project Status

**Status:** Production / Live  
The portfolio is fully deployed, validated, and publicly accessible.

---

## Deployment

- **Deployment Platform:** GitHub Pages
- **Live Production URL:** [https://arpit-jindal-01.github.io/profolio/](https://arpit-jindal-01.github.io/profolio/)
- **Repository:** [https://github.com/Arpit-Jindal-01/profolio](https://github.com/Arpit-Jindal-01/profolio)

---

## Development & Local Preview

To run and view this static portfolio locally:

```bash
# Clone the repository
git clone https://github.com/Arpit-Jindal-01/profolio.git
cd profolio

# Start a local HTTP server
python3 -m http.server 8080
```

Then open `http://localhost:8080/index.html` in your browser.

---

## Project Structure

```text
profolio/
├── ARPiT_FREELANCE/             — Organized freelance asset library (not deployed)
│   ├── DESIGN/
│   ├── EXCEL/
│   ├── VIDEO/
│   ├── CLIENT-SAMPLES/
│   └── PROPOSALS/
│       └── RATE-CARD.md
├── assets/
│   ├── design_breakfast_poster.png
│   ├── design_crispy_poster.png
│   ├── design_crispy_social.png
│   ├── design_iced_latte.png
│   ├── design_lemonade.png
│   ├── design_promo_creative.png
│   ├── money_matters_unstop.mp4
│   └── video_poster.jpg
├── .gitignore
├── index.html
├── README.md
└── vercel.json
```

---

## Implementation Notes

- **Contact Enquiry Flow:** Uses a client-side mailto system that formats and safely encodes project inquiry details into the user's default email application without external backend dependencies.
- **Dynamic Platform Rendering:** Fiverr and Upwork contact cards are conditionally hidden until URL strings are added to the JavaScript `CONTACT` object.
- **Data Privacy & Synthetic Projects:** Data portfolio items are built with synthetic business datasets to respect client data privacy and are clearly marked with `SAMPLE PROJECT` and `SYNTHETIC DATA` badges.
- **No Fabricated Claims:** All statistics, credentials, badges, and project descriptions represent authentic work and techniques without fabricated metric claims.
