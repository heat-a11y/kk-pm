# SJKC Pin Min — Co-Curricular Management System 2026

A responsive Single Page Application (SPA) dashboard for managing co-curricular activities at SJKC Pin Min. Built with HTML5, Tailwind CSS, and Alpine.js.

## Features

- **Dashboard** — Overview of active clubs, teachers, and cumulative attendance
- **Attendance System (Kehadiran)** — Club/date filtering with student check-in/check-out and localStorage persistence
- **Activity Hub** — 63 pre-loaded activities across 3 clubs (Badminton, PBSM, Bola Keranjang) with checklist tracking and custom activity form
- **OPR Report Generator** — One-page report (Laporan Satu Muka Surat) with club metadata and checkbox-selected activity highlights. Print-ready with `@media print` support.
- **OPC Coaching Panel** — Formal coaching letter (Bimbingan Satu Muka Surat) from GKKK with signature block and export to PDF

## Tech Stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) (CDN)
- [Alpine.js](https://alpinejs.dev/) (CDN)
- Vanilla JavaScript
- localStorage for offline data persistence

## Usage

Open `index.html` in any modern browser. No build step or server required.

## Deployment

The app is a single static HTML file. Deploy to any static host (Vercel, Netlify, GitHub Pages) by pointing to the repository root.
