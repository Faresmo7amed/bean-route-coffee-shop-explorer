# Bean Route ☕

🌐 **Live Demo:** https://bean-route-coffee-shop-explorer.pages.dev

A multi-page coffee shop directory built using **pure HTML5**.

The project presents a fictional coffee shop platform where users can browse a directory of Cairo coffee shops, read in-depth shop profiles, follow step-by-step home brewing guides, and submit a shop or get in touch through contact forms.

## Overview

Bean Route is a semantic, multi-page HTML project created to practice building a complete linked website without using CSS or JavaScript.

The goal of this project was to focus on:
- Multi-page site structure and navigation
- Semantic HTML5 elements
- Tables for structured data
- Media elements
- Forms and input types
- Linking within and across pages (including anchor links into another file)
- Proper use of HTML attributes

## Pages

### 🏠 `index.html` — Home
- Welcome section using text-formatting elements (`<strong>`, `<em>`, `<mark>`, `<small>`, `<del>`, `<ins>`)
- Embedded HTML5 video with poster fallback
- "This Week's Pick" featured shop with `<figure>`/`<figcaption>`
- Customer `<blockquote>` with ``
- Quick links to every other page

### 📋 `shops.html` — Shop Directory
- Full shop catalog in a `<table>` with `<thead>`, `<tbody>`, and a `<tfoot>` summary row
- Shop names link directly into specific sections of `shop-detail.html`
- "Browse by Area" list

### 📖 `shop-detail.html` — Shop Profiles
- Five in-depth shop write-ups as `<article>` elements, each with its own anchor `id`
- Photo galleries using `<figure>`/`<figcaption>`
- `<dl>` for address, hours, Wi-Fi, and seating details
- Customer `<blockquote>` reviews
- Embedded Google Maps `<iframe>` per shop
- Footnote-style citations (`<sup>`) linking to a shared sources section

### ☕ `brewing-guides.html` — Brewing Guides
- Three brewing methods: Pour-Over, French Press, Espresso
- Equipment lists (`<ul>`) and numbered steps (`<ol>`)
- Embedded demo `<video>` per method
- A comparison `<table>` across all three methods

### ✉️ `submit.html` — Submit & Contact
- "Submit a Coffee Shop" form with many input types
- A separate "Contact Us" form on the same page
- Embedded Google Maps `<iframe>` for the Bean Route location

## Technologies Used

- HTML5

No external libraries, frameworks, CSS, or JavaScript were used.

## Semantic HTML Elements Practiced

This project uses many HTML5 semantic and structural elements across its five pages:
- `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- `<figure>`, `<figcaption>`
- `<video>`, `<iframe>`
- `<table>` / `<thead>` / `<tbody>` / `<tfoot>`
- `<address>`
- `<blockquote>` / `<cite>`
- `<dl>`
- `<form>`, `<fieldset>`, `<legend>`

## Notes

This project intentionally uses some deprecated HTML tags and attributes:
- `<center>`
- `leftmargin`
- `border`
- `cellpadding`
- `cellspacing`

They were used because no CSS was involved in this project, and they helped with basic visual formatting. In modern web development, these should be replaced with CSS.

Every page repeats the same `<header>`, `<nav>`, and `<footer>` structure by hand rather than through a template or component system, since no CSS or JavaScript was used. Links between pages use relative paths, so all five HTML files must stay in the same folder for navigation to work correctly.

## Project Purpose

This project is part of my HTML learning journey and focuses on understanding how a multi-page website is structured and linked using semantic HTML, before adding styling and interactivity.

## Future Improvements

Possible improvements:
- Add responsive CSS styling
- Add JavaScript form validation
- Connect the submission and contact forms to a backend
- Add dynamic shop data using an API
- Add Web Accessibility (ARIA roles and attributes)

## Author

**Fares Mohamed**

© 2026 Bean Route