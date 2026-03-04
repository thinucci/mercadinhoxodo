# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

Static landing page for **Mercadinho Xodó – Doces Baiano**, a Brazilian sweets shop in São Paulo. No build tools, frameworks, or dependencies — open `index.html` directly in a browser to preview.

## Structure

- `index.html` — single-page site, all sections in one file
- `style.css` — all styles, organized by section with `/* ── SECTION ── */` comments
- `img/` — product photos used in hero and gallery
- Root-level images (`Mercadinho xodo.png`, etc.) — used in the Sobre section

## Design tokens (CSS variables)

Defined in `:root` in `style.css`:

| Variable | Value | Usage |
|---|---|---|
| `--brown` | `#5C3317` | Nav, headings, footer |
| `--yellow` | `#FFD700` | Accents, logo, CTA nav button |
| `--orange` | `#FF6B35` | Primary buttons, eyebrow text |
| `--pink` | `#FF4D6D` | Button hover state |
| `--cream` | `#FFF8F0` | Page background |
| `--radius` | `20px` | Border radius for cards/images |

## Page sections (in order)

1. **NAV** — sticky, brown background, links to `#produtos`, `#sobre`, `#galeria`, `#contato`; "Peça agora" links to Goomer ordering app
2. **HERO** — two-column grid (text + image with yellow blob behind); image is `img/2.jpg`
3. **PRODUTOS** — brown background, 4 product cards with emoji icons
4. **SOBRE** — two-column grid (image + text); image is `Mercadinho xodo.png`
5. **GALERIA** — 3-column CSS grid with `.tall` (row span 2) and `.wide` (col span 2) modifiers
6. **CONTATO** — 4-item info grid (address, phone, hours, Instagram)
7. **FOOTER**

## Fonts

Loaded from Google Fonts (no local install needed):
- `Pacifico` — used for headings and logo
- `Nunito` — body text (weights 400, 700, 900)

## Business info

- Address: R. Piqueri, 42 - Freguesia do Ó, São Paulo - SP, 02925-070
- Phone/WhatsApp: (11) 99247-1031 → `https://wa.me/5511992471031`
- Ordering app: `https://mercadinho-xodo.goomer.app`
- Instagram: @mercadinhoxodo
