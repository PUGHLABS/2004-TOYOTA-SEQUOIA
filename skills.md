# 2004 Toyota Sequoia — Project Skills & Context

## Vehicle
- **Year/Make/Model:** 2004 Toyota Sequoia 4X4 Limited
- **VIN:** 5TDBT48A14S230766
- **Engine:** 4.7L V8 2UZ-FE
- **Transmission:** 4-speed automatic A750F (4WD)
- **Color:** Phantom Gray Pearl
- **Owner:** Spokane, WA 99203
- **Customer #:** 8020698 (Findlay/LHM dealer system)
- **Purchased:** 02-22-2022, Spokane WA — $10,000 @ 100,927 mi (do not name the dealer)
- **Current Mileage:** 173,986 mi

## Project
Local HTML service dashboard (`index.html`) consolidating all service records. Goal is 100% verified data from 53 scanned invoice images.

- **Layout:** Dashboard Split View (Layout A) — left panel = recommended work, right panel = service history
- **Theme:** Dark default (`#002451` bg, `#ff7900` accent) with light mode toggle
- **CSS:** Separated into `styles.css` (linked from index.html)
- **Data source:** 53 JPG images in `sequoia pdfs/` + `factory maintence schedule.pdf`

## Primary Dealers
- **Findlay Toyota Spokane** — 1128 W 3rd Ave, Spokane WA 99201 — (509) 455-8770 — current dealer
- **Larry H. Miller Downtown Toyota Spokane** — same address — former name (pre ~mid-2022)
- **Don Ringler Toyota** — Temple, TX — used Dec 2021 (owner was in Texas)

## Key Rules
- Camshaft seals and rear crankshaft seal are **SEPARATE jobs** (different labor, different access)
- Costco tires total = $1,086 (confirmed)
- Steering rack **REPLACED** Oct 2024 — PS hoses still original and separate
- CV axles **REPLACED** Oct 2024, then **REPLACED AGAIN** ~171,100 mi (DIY, both front)
- Front diff axle seals **DONE** ~171,100 mi (DIY, with the new axles)
- Front diff needle bearing **DONE** ~171,100 mi (DIY — East Coast Gear Supply, $206.41)
- PS return line **DONE** ~171,100 mi — was just a loose hose clamp, no replacement (dealer had quoted $1,386.05)
- DIY batch @ ~171,100 mi: front rotors 2 × $57.92, PowerStop front pads $57.43/pair, weatherstrip $49.99 (first set returned defective), front turn signal lights $50.99/pair, fuel door spring $8.82
- Wheel bearings were purchased but **RETURNED** — never list them as installed
- Front struts replaced **Oct 2024** (NOT March 2022)
- Timing belt done **March 2022 @ 139,367 mi** (Larry H. Miller)
- Invoice #409384 (Jun 2025) = fuel sending unit replacement, NOT transmission/diff service
- Do not include dealer name for the purchase — just city and state

## Factory Maintenance Schedule (SUV/Truck 4WD)
- **Every 5k:** Oil change + tire rotation
- **Every 5–15k:** Propeller shaft lubrication (4WD — CRITICAL, no records ever found)
- **30k:** Spark plugs (Sequoia explicitly listed), air filter
- **60k:** Initial timing belt inspection
- **90k:** Replace timing belt + spark plugs
- **100k:** Replace engine coolant (then every 50k)

## Outstanding Recommended Work (as of Nov 2026 @ 173,986 mi)
Priority: safety → longevity → cost

1. Brake Fluid Flush — ~$200 (last done Oct 2022 @ ~144,500 mi)
2. PS Pressure Hose — $209.95 (Feb 2026, noted "clean and recheck")
3. Rear Struts — $883 (Feb 2026 pre-work order)
4. Camshaft Seals (both banks, labor only) — $1,480 (Feb 2026)
5. Rear Crankshaft Seal — $1,808.63 (Feb 2026 pre-work order)
6. Spark Plugs (8 plugs, V8) — ~$400–500 (24k overdue)
7. Engine Coolant — ~$150–200 (24k overdue)
8. Propeller Shaft Lubrication — ~$30 (no records ever found)
9. Oil Change + Rotation — ~$210 (due now, ~174,000 mi)

## Files
- `index.html` — main dashboard (links to styles.css)
- `styles.css` — all CSS (dark/light theme variables + layout)
- `FSD.md` — original project brief
- `skills.md` — this file
- `sequoia pdfs/` — 53 JPG images of service invoices (all dated 20260412_*.jpg)
- `factory maintence schedule.pdf` — Toyota factory maintenance schedule PDF
