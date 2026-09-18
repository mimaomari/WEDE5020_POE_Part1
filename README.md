# Define By Nature - Sustainable Urban Streetwear

## Student Information
- **Student Name:** Mima Omari
- **Module:** WEDE5020 - Web Development (Introduction)
- **Qualification:** Higher Certificate in Mobile Application and Web Development
- **Institution:** The Independent Institute of Education 
- **Year:** 2026

---

## Project Overview
**Define By Nature** is a contemporary, eco-conscious streetwear apparel brand created to offer minimalist, sustainably produced urban fashion for South African youth. This repository houses the front-end source code, initial semantic structure, and planning documentation for the brand's official multi-page web platform developed for WEDE5020 Portfolio of Evidence (POE) Part 1.

---

## Website Goals and Objectives
- **Brand Identity & Storytelling:** Articulate the label's ethos, origin, and commitment to sustainable textiles through accessible web content.
- **Product Showcase:** Display seasonal lookbook collections with descriptions, garment materials, and transparent pricing.
- **Customer & Partner Engagement:** Enable prospective customers, stockists, and collaborators to submit product or wholesale inquiries easily.
- **Location Accessibility:** Provide structured contact details and address references for physical studio hubs in Cape Town and Johannesburg.
- **Standards & Code Quality:** Build a fully semantic HTML5 structure that follows WCAG 2.2 accessibility standards and clean separation of concerns.

---

## Key Features and Functionality
- **Cross-Page Navigation:** Consistent `<nav>` menu linking all five core pages across the platform.
- **Hero & Call-to-Action:** High-visibility introductory section on the home page directing users to the apparel collection.
- **Accessible Forms:** Input forms on the Enquiry and Contact pages utilizing paired `<label>` and `<input>`/`<textarea>` elements.
- **Multi-Branch Directory:** Detailed physical location records for both Cape Town and Johannesburg locations.
- **Semantic HTML5 Layout:** Proper use of semantic page elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) with descriptive structural comments.

---

## Timeline and Milestones

| Milestone | Planned Timeline | Status | Deliverables & Focus Area |
| :--- | :--- | :--- | :--- |
| **Part 1** | August 2026 | **Completed** | Project initiation, topic proposals, sitemaps, semantic HTML skeleton, and Git repository initialization. |
| **Part 2** | September 2026 | *Pending* | External CSS styling, responsive layout (Flexbox & CSS Grid), typography, and color schemes. |
| **Part 3** | October 2026 | *Pending* | Interactive JavaScript features, form validation, micro-animations, and final hosting deployment. |

---

## Part 1 Details
- Initialized a structured directory tree with root folders: `css/`, `js/`, `images/`, `docs/`, and `research/`.
- Authored 5 core semantic HTML pages:
  - `index.html` (Homepage with hero section, introduction, and CTA)
  - `about.html` (Brand history, mission, vision, and team structure)
  - `services.html` (Seasonal apparel catalog with product descriptions and pricing)
  - `enquiry.html` (Interactive product and wholesale enquiry form)
  - `contact.html` (Contact directory with details for two physical locations and message form)
- Formatted and validated semantic HTML markup with descriptive structural comments.
- Compiled research documentation and institutional references.

---

## Sitemap
The visual sitemap hierarchy illustrates the parent-to-child relationship between the central Homepage and its subpages:

```text
                               +-----------------------+
                               |       Homepage        |
                               |     (index.html)      |
                               +-----------+-----------+
                                           |
         +-----------------+---------------+-----------------+-----------------+
         |                 |                                 |                 |
+--------+--------++-------+--------+               +--------+--------++-------+--------+
|    About Us     || Products/Srv.  |               |    Enquiry      ||    Contact     |
|  (about.html)   || (services.html)|               |  (enquiry.html) ||  (contact.html) |
+-----------------++----------------+               +-----------------++--------+-------+
                                                                                |
                                                                   +------------+------------+
                                                                   |                         |
                                                            +------+------+           +------+------+
                                                            |  Cape Town  |           | Johannesburg|
                                                            |   Studio    |           |   Pop-Up    |
                                                            +-------------+           +-------------+
 Google Fonts (2026). Montserrat & Inter Typeface Pairings. Available at: https://fonts.google.com (Accessed: 15 August 2026).

Unsplash (2026). Urban Fashion and Streetwear Photography Collection. Available at: https://unsplash.com (Accessed: 15 August 2026).

W3C (2023). HTML5 Semantic Elements Specification. Available at: https://www.w3.org/TR/html52/ (Accessed: 15 August 2026).

World Wide Web Consortium (2024). Web Content Accessibility Guidelines (WCAG) 2.2. Available at: https://www.w3.org/WAI/standards-guidelines/wcag/ (Accessed: 15 August 2026). 

# Web Development Portfolio - Part 2 Implementation

## 1. Changelog (Part 1 Feedback Addressed)
- **Home Navigation:** Aligned `index.html` navigation links to include all site pages (About Us, Products & Services, Enquiry, Contact).
- **Structural Comments:** Embedded structural semantic comments (`HEADER`, `MAIN`, `SECTION`, `FOOTER`) into all secondary HTML pages.
- **Folder & Asset Consistency:** Standardized script and stylesheet naming conventions and file paths.
- **Proposal Documentation:** Embedded Harvard-style in-text citations and included wireframe assets in the documentation repository.

## 2. CSS Styling & Layout Architecture
- **CSS Reset & Custom Properties:** Implemented a full box-sizing reset and reusable root variables for colors and typography.
- **Fluid Typography:** Formatted heading and text scales using relative `rem` units and fluid percentage container widths.
- **Grid & Flexbox:** Configured Flexbox navigation bars and multi-column CSS Grid card layouts.
- **Micro-Interactions:** Added pseudo-classes (`:hover`, `:focus`, `:active`) to enhance interactivity across links and buttons.

## 3. Responsive Breakpoints & Testing Evidence
The application was tested across three viewports using browser DevTools:
- **Desktop (> 992px):** Multi-column grid layout, horizontal navigation bar.
- **Tablet (601px - 992px):** Responsive grid layout, fluid typography.
- **Mobile (<= 600px):** Single-column stacked layout, touch-friendly navigation links.

### Visual Evidence:
![Desktop View](screenshots/desktop%20view.PNG)
![Tablet View](screenshots/tablet%20view.PNG)
![Mobile View](screenshots/mobile%20view.PNG)

## 4. References
- Mozilla Developer Network (MDN). (2024). *CSS Grid Layout*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout (Accessed: 18 September 2026).
- Mozilla Developer Network (MDN). (2024). *Responsive images*. Available at: https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images (Accessed: 18 September 2026).
- World Wide Web Consortium (W3C). (2023). *CSS Flexible Box Layout Module Level 1*. Available at: https://www.w3.org/TR/css-flexbox-1/ (Accessed: 18 September 2026).