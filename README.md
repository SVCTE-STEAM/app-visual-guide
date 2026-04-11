# Web App Features — Interactive Visual Guide

An interactive, single-page reference for developers and students learning how modern web applications are built. Every feature is demonstrated live — not just described — with hover callouts explaining what each element does and why it exists.

Deployable to GitHub Pages with no build step, no framework, and no dependencies.

---

## What's Inside

### Frontend
Real, working demos of the most common UI patterns:

- **Responsive Layout** — breakpoint simulator (Mobile / Tablet / Desktop)
- **Dark / Light Mode** — full theme switch via CSS variables, persisted to `localStorage`
- **Skeleton Loaders** — shimmer animation for loading states
- **Toast Notifications** — success, error, and info variants
- **Form Validation** — inline error and valid states
- **Search Autocomplete** — live filtered suggestions as you type
- **Drag & Drop Upload** — drop zone with file list
- **Sortable Data Table** — click column headers to sort
- **Modal Dialog** — backdrop blur, ESC to close, focus trap
- **Tab Panels** — content switching without page reload
- **Infinite Scroll** — simulated lazy loading on scroll
- **Progress Bars** — animated fill on load
- **Nav Drawer** — hamburger trigger, slide-in panel, backdrop dismiss, animated ☰ → ✕

### Auth UI
- **Login Form** — email/password, show/hide toggle, OAuth buttons
- **Sign Up Form** — with live password strength meter
- **Password Strength Meter** — real-time scoring with rule checklist
- **Forgot Password Flow** — animated 4-step walkthrough with server-side annotations

### Backend
Annotated diagrams of server-side patterns:

- **Auth Flow** — credential → hash verify → MFA → JWT issuance
- **Role-Based Access Control** — Admin / Editor / Viewer permission grid
- **REST API Endpoints** — GET / POST / PUT / DELETE with status codes
- **Rate Limiting** — live sliding-window meter with countdown
- **Webhooks** — event payload examples
- **Cache Layer** — HIT / MISS visualization with timing
- **Background Job Queue** — done / running / pending states
- **Database Schema Viewer** — click between tables to inspect columns, types, constraints, and relationships

### HTTPS Lifecycle
Animated simulation of a real HTTPS request from start to finish:

- **Phase pipeline** — DNS → TCP → TLS → Request → TTFB → Download, animated sequentially
- **9 status code scenarios** — 200, 201, 301, 401, 403, 404, 429, 500, 503
- **Request inspector** — full HTTP headers with per-header callouts
- **Response inspector** — status badge, headers, syntax-highlighted JSON body
- **Waterfall timing bar** — proportional segment chart matching Chrome DevTools style
- **Error panel** — plain-English explanation of each error, retry guidance
- **Request log** — persistent history of all simulated requests

---

## How to Use

**Online:** Open the deployed GitHub Pages link in any modern browser.

**Locally:** Download `index.html` and open it directly — no server required.

**Hover** any labeled element to see a callout explaining what it is and how it works in a real application.

---

## Deploying to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Save — your guide will be live at `https://yourusername.github.io/repo-name`

---

## Goals

This project is built for:
- **Students** learning web development who want to see patterns in context, not just read about them
- **Instructors** looking for a live reference to use alongside curriculum
- **Developers** who want a quick visual refresher on a pattern or HTTP behavior

---

## Tech

| | |
|---|---|
| Languages | HTML, CSS, JavaScript |
| Dependencies | None |
| Build step | None |
| File count | 1 |
| Fonts | Syne, DM Mono (Google Fonts) |

---

## Contributing

Issues and pull requests welcome. When adding a new demo card:

- Every interactive element should have a `data-tip` attribute
- Demos should be functional, not cosmetic — if it looks like it does something, it should do it
- Keep all code in `index.html` — no build tooling, no bundlers

---

## License

MIT
