# Off-Grid Solar & Battery Bank Sizing Calculator ⚡

> Interactive off-grid solar and battery bank sizing utility. Calculates daily Watt-hours, LiFePO4/AGM Amp-Hours, and solar panel requirements with zero dependencies.

A fast, client-side engineering utility built for campers, van-lifers, RVers, and off-grid homeowners to accurately estimate their solar array and battery storage requirements.

---

## Features

- **Dynamic Appliance Load Modeling:** Add custom AC/DC devices or choose from common presets (12V compressor fridges, Starlink, CPAP machines, laptops, lighting, etc.).
- **Battery Chemistry & DoD Sizing:** Supports LiFePO4 Lithium (85% recommended DoD) and AGM / Sealed Lead-Acid (50% max DoD) with custom Depth of Discharge overrides.
- **Multi-Voltage Support:** Instant recalculations across 12V, 24V, and 48V battery architectures.
- **Environmental Parameters:** Factoring in days of autonomy (backup overcast days), inverter efficiency, and regional average peak sun hours.
- **Hardware Procurement Guide:** Translates raw capacity math into practical equipment counts (e.g. 100Ah/200Ah battery counts and 100W/200W/400W solar panels).
- **One-Click Spec Export:** Copy complete electrical specifications directly to the clipboard for contractor quotes or component shopping.
- **SEO & Search Rich Snippets:** Built-in Schema.org `WebApplication` and `FAQPage` JSON-LD structured data.
- **Compliance & Privacy:** Full Google AdSense policy disclosures, terms of use disclaimer, and `ads.txt` integration.

---

## Technology Stack

- **HTML5 & CSS3:** Responsive modern dark theme, CSS Grid & Flexbox, mobile-friendly (touch-optimized inputs).
- **Vanilla JavaScript:** 100% in-browser, defensive client-side execution with zero external frameworks, npm packages, or CDN dependencies.

---

## Local Development & Usage

No installation or build steps are required. Simply open `index.html` in any modern web browser:

```bash
# Clone the repository
git clone https://github.com/<your-username>/solar-battery-calculator.git

# Open directly in browser
open index.html # macOS
start index.html # Windows
```

---

## License

This project is open-source and available under the [MIT License](LICENSE).
