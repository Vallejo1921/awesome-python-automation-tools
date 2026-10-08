# ⚡ Awesome Python Automation & Scraping Tools

> A curated collection of battle-tested, lightweight automation scripts, web scrapers, and data cleaning pipelines designed for developers, freelancers, and small businesses.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Support with PayPal](https://img.shields.io/badge/Support_Project-PayPal-00457C?style=flat&logo=paypal)](https://paypal.me/maxter19)

---

## 🛠️ Included Tools & Scripts

### 1. 🕷️ [Universal Web Scraper](scrapers_toolkit/universal_scraper.py)
A resilient, zero-bloat web scraper that parses web pages and exports clean, structured datasets to multiple formats:
- **Formats supported**: CSV (UTF-8 with BOM for Excel), JSON, and local SQLite database.
- **Anti-blocking headers**: Built-in User-Agent rotation and response decoding.

```bash
python3 scrapers_toolkit/universal_scraper.py
```

### 2. 🧹 [Automated CSV/Excel Cleaner & Deduplicator](scrapers_toolkit/csv_cleaner.py)
Automates messy spreadsheet cleanup in seconds:
- Strips excess whitespace and irregular line breaks.
- Normalizes international phone number formatting (e.g., E.164 / Mexican local prefixes).
- Drops duplicate rows based on unique column keys.

```bash
python3 scrapers_toolkit/csv_cleaner.py dirty_leads.csv clean_leads.csv email
```

### 3. 🎨 [High-Converting Tailwind Landing Template](landing_templates/index.html)
A lightning-fast, single-page landing site designed for immediate customer conversion with WhatsApp and PayPal checkout integration.

---

## 💼 Commercial Software & Live Services

If you need full turnkey business solutions, check out our live products:

- 🛒 **[Caja POS PyME Pro](https://vallejo1921.github.io/caja-pos-pyme/)**: Lifetime offline Point of Sale for retail shops & freelancers ($99 MXN / $5 USD, 0 monthly fees).
- 🌐 **[Custom Software & Scraping Services](https://vallejo1921.github.io/servicios-software/)**: Need a custom script or data extraction pipeline built for your company? Get a quote in 15 minutes.

---

## ☕ Support & Sponsorship
If these scripts saved you hours of work, consider supporting the open-source development:
- **PayPal Tip / Donation**: [paypal.me/maxter19](https://paypal.me/maxter19)
- **Stellar (USDC / XLM)**: `GDMZUBNE4MH7WX4TO62E2VT6XZDFOYQW42IPT7TMCN2QLBUCYFP4BTAP`

---

## 📄 License
MIT License. Free to use, adapt, and build upon for personal and commercial projects.
