# ✳ AURIX — Invoice Studio

A beautiful, fully functional **local-first invoice and client workspace** you can host for free using GitHub Pages.

![AURIX dashboard](docs/preview-desktop.png)

## Features

- Dashboard with KPIs, real charts and invoice breakdowns
- Add / edit / delete clients with client-level billing totals
- Create / edit / duplicate / delete invoices with line items and tax
- Draft, Sent, Paid, and automatically derived Overdue states
- Invoice preview + browser **Print / Save as PDF**
- Search and filter invoices and clients
- Business details, invoice prefix and currency preferences
- Download a CSV invoice report
- JSON workspace backup and restore
- Light and dark mode
- Responsive desktop and mobile navigation
- Built with vanilla HTML, CSS, and JavaScript — no dependencies or build step

## Getting started

Open `index.html` in your browser. That's it. For a better local developer workflow use VS Code and the Live Server extension.

**GitHub Pages:** Push all files to a public repository (with `index.html` at its root), then go to **Settings → Pages → Deploy from a branch → main / (root)**.

## Important notes

- AURIX stores all information in **your browser's localStorage**. It has **no backend, login, payments integration, cloud sync, or email sending**.
- Sample client/invoice entries use `example.com` addresses and are **demo data**, not real customers.
- Use **Settings → Start empty** to clear the sample entries, or **Settings → Restore demo** to reset. Export a backup first if needed.
- The dashboard/report amounts use the current settings currency. **Changing currency does not convert invoice values**.
- **Print / PDF** opens your browser print dialog; choose **Save as PDF** as the destination.
- Printing your invoice depends on your browser print layout. Test the result before sending externally.
- This is a demonstration app. Do not store sensitive business details in a shared browser.

## Shortcuts

- `/` — focus search
- `N` — new invoice
- `Escape` — close an open dialog

## Tech stack

HTML5 · CSS3 · JavaScript ES2022 · SVG · Web Storage

## License

MIT — adapt this project for your portfolio.
