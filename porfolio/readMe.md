# Responsive Personal Portfolio Website

A 3-page responsive personal portfolio website built using pure semantic HTML5 and modern CSS3. Developed as an academic assignment for the **Web Programming** course in the Master of Computer Applications (MCA) program.

---

## Overview

The objective of this project is to implement core web layout paradigms—specifically CSS Grid and Flexbox—without relying on external frameworks or JavaScript. The site provides a cohesive identity across three distinct pages sharing a single global stylesheet, adapting across desktop and mobile viewports.

---

## Key Features

- **Semantic Multi-Page Architecture**:
  - `index.html`: Home page featuring developer identity, image placeholder, and technical tagline.
  - `projects.html`: Portfolio gallery showcasing project cards laid out using CSS Grid (minimum 3 cards).
  - `contact.html`: Clean contact form (Name, Email, Message) structured and aligned using Flexbox.
- **Unified Layout Shell**:
  - Persistent header with branding/logo and navigation menu across all pages.
  - Standardized footer with contact details consistent on every page.
- **Pure CSS Layout & Responsiveness**:
  - **CSS Grid**: Manages the multi-column card layout on the Projects page.
  - **Flexbox**: Used for the header navigation, hero content alignment, and contact form inputs.
  - **Media Queries**: Responsive breakpoints optimized for desktop screens (`>1024px`) and mobile devices (`<480px`).

---

## Tech Stack

- **Markup**: HTML5 (Semantic elements)
- **Styling**: CSS3 (CSS Grid, Flexbox, Media Queries)
- **Tools**: VS Code, Git, Microsoft Edge / Chromium DevTools

---

## File Structure

```text
├── contact.html          # Contact page with Flexbox form
├── contact_desktop.png   # Contact page screenshot (Desktop view)
├── contact_mobile.png    # Contact page screenshot (Mobile view)
├── index.html            # Home page (Hero section, bio, tagline)
├── index_desktop.png     # Home page screenshot (Desktop view)
├── index_mobile.png      # Home page screenshot (Mobile view)
├── projects.html         # Projects page with CSS Grid cards
├── projects_desktop.png  # Projects page screenshot (Desktop view)
├── projects_mobile.png   # Projects page screenshot (Mobile view)
├── style.css             # Unified stylesheet across all pages
└── README.md             # Project documentation