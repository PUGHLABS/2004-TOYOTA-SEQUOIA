# 2004 Toyota Sequoia — Service Dashboard

A self-contained local web dashboard that consolidates the complete service history for a 2004 Toyota Sequoia 4X4 Limited. Built from 53 scanned dealer invoices and cross-referenced against the Toyota factory maintenance schedule.

## Live Site
**[https://pughlabs.github.io/2004-TOYOTA-SEQUOIA/](https://pughlabs.github.io/2004-TOYOTA-SEQUOIA/)**

---

## Vehicle
| | |
|---|---|
| **Year / Make / Model** | 2004 Toyota Sequoia 4X4 Limited |
| **Engine** | 4.7L V8 2UZ-FE |
| **Transmission** | 4-speed automatic A750F (4WD) |
| **Color** | Phantom Gray Pearl |
| **VIN** | 5TDBT48A14S230766 |
| **Current Mileage** | 173,986 mi |

---

## Features

- **Split-panel dashboard** — recommended work on the left, full service history on the right
- **Dark / Light mode toggle** — dark default (`#002451` navy + `#ff7900` orange accent)
- **Priority-coded recommended work** — Safety (red), Longevity (yellow), Factory Overdue (purple), Maintenance (green)
- **Factory maintenance tracker** — every interval cross-referenced against completed services, with Overdue / Due Soon / Upcoming / Done status badges
- **Complete service history** — 19 entries from 2010 purchase through the ~171,100 mi DIY work in 2026, with exact mileage, invoice numbers, shop names, line items, and totals
- **Quoted remaining work** — all outstanding items include actual dealer quotes with source invoice references
- **Glam Shots tab** — photo gallery with lightbox and video, loaded only when the tab is opened
- **No dependencies** — single `index.html` + `styles.css`, no frameworks, no build step, works offline

---

## Data Sources

- **53 scanned JPG images** of dealer service invoices (`sequoia invoice pics/`)
- **Toyota factory maintenance schedule PDF** (`factory maintenance schedule.pdf`)
- All data verified directly from invoice images — no estimates or assumptions

---

## Service Summary

| Category | Amount |
|---|---|
| Purchase price | $10,000 |
| Total documented service spend | ~$10,363 |
| Estimated remaining work | ~$5,505–5,665 |

### Top Outstanding Items
1. Brake Fluid Flush — ~$200
2. Power Steering Pressure Hose — $209.95
3. Rear Struts — $883
4. Camshaft Seals — $1,480
5. Rear Crankshaft Seal — $1,808
6. Spark Plugs — ~$400–500 *(24k overdue)*
7. Engine Coolant — ~$150–200 *(24k overdue)*

---

## Primary Dealer
**Findlay Toyota Spokane** (formerly Larry H. Miller Downtown Toyota Spokane)
1128 W 3rd Ave, Spokane, WA 99201 — (509) 455-8770

---

## Files

```
index.html                     — Dashboard (links to styles.css)
styles.css                     — All CSS with dark/light theme variables
skills.md                      — Project context and key rules
FSD.md                         — Original project brief
factory maintenance schedule.pdf — Toyota factory maintenance PDF
sequoia invoice pics/          — scanned service invoice images
glam/                          — Glam Shots gallery (web-sized photos, thumbnails, video)
2001-2007 Toyota Sequoia.pdf   — Sequoia reference manual
Sequoia_Front_End_Vibration_Road_Diagnostic.pdf — front-end vibration diagnostic
seq 4x4 sequence.md            — 4x4 system notes
```

---

*Built with Claude Code — data verified from source invoices.*
