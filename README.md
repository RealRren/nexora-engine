# Nexora Engine

> Business documents, estimating tools and calculators for contractors, in one app that works on the web and on Windows, online or offline.

![Nexora Engine Home](docs/screenshots/home-dark-1920.png)

**[Download for Windows](https://github.com/RealRren/nexora-engine-releases/releases/latest)** · **[Nexora Downloade page](https://github.com/RealRren/nexora-engine-releases/releases/latest)**

> This is a **showcase** repository. The source code is private. This page shows what the app does and how it was built.

---

## What it does

**Business documents (ERP)**
- Quotation, Pro Forma Invoice, Tax / Commercial Invoice, Delivery Note
- Totals, discount, VAT and freight calculated automatically
- Print to PDF exactly as shown on screen
- Export to Excel (.xlsx), verified in real Microsoft Excel

**Canva-style document editor**
- Move, resize, layer and overlap any element
- Insert text boxes, tables, images, shapes and extra pages
- Text tools: fonts, colours, lists, spacing, borders
- Copy / paste, multi-select, right-click menu, full undo/redo
- Figures always stay tied to the form, so edits can't break the totals

**Estimating tools and calculators**
- BOQ, Qty & Rate, Variation Order, Import Tax, Scope Guard report
- Calculator reports ready to print

**Account and cloud**
- Sign up with an emailed code, password reset by code
- Library of saved documents, synced to your account
- Free and Premium plans
- Support tickets inside the app

**Everywhere**
- Web app (installable, works offline)
- Windows desktop app with automatic update check
- Dark and light themes
- Sinhala and Tamil text supported

---

## Screenshots

| | |
|---|---|
| ![Home](docs/screenshots/home-light-1280.png) | ![Quotation](docs/screenshots/quotation.png) |
| Home dashboard | Quotation |
| ![Tax Invoice](docs/screenshots/tax-invoice.png) | ![Excel export](docs/screenshots/excel-export.png) |
| Tax Invoice | Excel export |
| ![Editor](docs/screenshots/editor.png) | ![Mobile](docs/screenshots/mobile-375.png) |
| Document editor | Phone layout |

![Editor demo](docs/screenshots/editor-demo.gif)

*All screenshots use demo data.*

---

## Built with

| Area | Technology |
|---|---|
| Front end | HTML, CSS, JavaScript |
| Offline / installable | Service worker (PWA) |
| Auth and database | Supabase (Postgres, Row Level Security) |
| Web hosting | Vercel |
| Desktop | Windows desktop app with bundled web files |
| Releases | GitHub Releases + forced update check |
| Exports | PDF, Excel (.xlsx) |

## How it was built

- Built with AI-assisted development: I planned each task, wrote the specs and acceptance checks, and reviewed every result before it was accepted.
- Every change runs through automated test sweeps (calculations, contrast/accessibility, login protection, Excel output, editor behaviour) before it is committed.
- Database access is locked down with Row Level Security: each user can only read and write their own rows.

---

## Status

Current release: **v0.1.1** · Next: **v0.1.2** (editor, templates, password reset)

## Contact

Made by **[RealRren](https://github.com/RealRren)**. For questions, open an issue in this repository.
