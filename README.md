# 🌿 The MayaNut Company Website
*MayaNut™ Flour • Alicastrum • Brosimum alicastrum • Tropical agroforestry • Reforestation*

<p align="center">
  <img src="https://mayanut.com/the-mayanut-company-logo-tm.png" width="200" alt="The MayaNut Company logo">
</p>

<p align="center">
  <strong>Website:</strong> <a href="https://mayanut.com">mayanut.com</a>
</p>

This repository contains the source for **The MayaNut Company** website — a fast, static, multi-page site built to introduce **MayaNut™ Flour**, a finely milled product made from the seeds of the Alicastrum tree (*Brosimum alicastrum*), and to support a clean, product-forward brand experience as the company grows.

The goal is straightforward: visitors should quickly understand **what MayaNut™ is**, move naturally toward **products**, and then explore deeper supporting pages only if they want more detail.

---

## Overview

The website serves as:

- a **product-first brand site** for The MayaNut Company
- an introduction to **MayaNut™ Flour** and the **Alicastrum** tree
- a foundation for **recipes, education, and supporting content**
- a static, performance-conscious site designed for **clarity, SEO, and long-term scalability**

Primary fieldwork, nursery development, and long-term cultivation efforts are based in **South Florida, USA**.

---

## Status

- 🚧 **Active development**
- 🌍 **Localized site structure** (English root; additional language paths in progress)
- ⚡ **Static hosting**
- ⛓️ **No framework dependencies** (vanilla HTML/CSS/JS)
- 🔍 **SEO-ready foundation** with structured metadata, semantic markup, and JSON-LD

---

## Current site goals

- clearly explain **What is MayaNut™?**
- support a strong **product-first experience**
- provide polished supporting pages such as **About**, **FAQ**, **Recipes**, and **Product**
- maintain a clean, premium visual identity across desktop and mobile
- preserve strong crawlability, metadata, and structured internal linking

---

## Key features

- Product-forward homepage with clear introductory positioning
- Responsive design for desktop, mobile, tablet, and mobile landscape
- Shared site-wide header, footer, and bottom mobile navigation
- Multi-page navigation across core pages
- Language selector with localized path structure
- Cart state persistence across pages via local storage
- FAQ accordion behavior with one item open at a time
- Performance-conscious image loading using `loading="lazy"` and `decoding="async"` where appropriate
- Static architecture designed for maintainability and fast hosting

---

## SEO and technical foundations

The site is built with strong technical hygiene in mind, including:

- clean page titles and meta descriptions
- canonical URLs
- robots directives
- Open Graph and Twitter metadata
- hreflang across localized paths
- semantic HTML
- JSON-LD structured data
- image alt text
- disciplined ARIA usage
- web manifest support
- mobile-first layout behavior
- lightweight vanilla JavaScript for UI interactions

Relevant structured data may include:

- `Organization`
- `WebSite`
- `WebPage`
- `AboutPage`
- `FAQPage`
- `Product`
- `BreadcrumbList`
- `CollectionPage`
- `ItemList`

Schema is only added where it reflects real content on the page.

---

## Tech stack

- **HTML5** — structure, semantics, crawlability
- **CSS3** — layout, typography, responsiveness, branding
- **Vanilla JavaScript** — menus, overlays, accordions, cart state, language panel, and UI interactions
- **GitHub Pages** — static hosting

---

## Repository structure

> Keep this section aligned with the actual repo as files evolve.

```txt
/
├─ index.html
├─ about.html
├─ faq.html
├─ recipes.html
├─ product.html
├─ privacy.html
├─ terms.html
│
├─ site.webmanifest
├─ robots.txt
├─ sitemap.xml
├─ README.md
│
├─ es/
├─ fr/
├─ pt/
├─ ru/
├─ zh-hans/
├─ hi/
│
├─ the-mayanut-company-logo-tm.svg
├─ the-mayanut-company-logo-tm.png
├─ the-mayanut-company-product-pouch.png
├─ mayanut-powder-maya-nut-brosimum-alicastrum.png
├─ august-kokus-augustkokus-mayanut-brosimum-alicastrum.jpeg
├─ maya-nut-mayanut-fruit-brosimum-alicastrum.jpg
├─ florida-image-the-maya-nut-company.png
└─ (other images and media assets)
