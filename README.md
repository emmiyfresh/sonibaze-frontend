# Sonibaze Frontend

A responsive static landing page for a digital agency brand, built with HTML and CSS. The project presents a polished homepage for Sonibaze Digital with sections for services, portfolio work, company information, news, testimonials, and contact details.

## Overview

This repository contains the front-end implementation of a modern marketing website. It focuses on a clean layout, strong typography, visual hierarchy, and reusable styling patterns. The design includes a dark hero section, service cards, project thumbnails, blog cards, testimonial blocks, and branded footer navigation.

## Features

- Responsive homepage layout
- Hero banner with call-to-action button
- Services overview section
- Portfolio/work showcase cards
- About us section with company information
- Latest news/blog cards
- Client testimonials
- Contact section and social media links
- Branded footer with navigation and contact details
- Static assets using local image files and external CDN styling

## Tech Stack

- HTML5
- CSS3
- Normalize.css
- Google Fonts
- Local image assets

## Project Structure

```bash
.
├── CSS_advanced/
│   └── style.css
├── images/
│   ├── favicon.png
│   ├── logo-black.png
│   ├── logo-white.png
│   ├── pic-about-01.jpg
│   ├── pic-article-01.jpg
│   ├── pic-article-02.jpg
│   ├── pic-article-03.jpg
│   ├── pic-person-01.jpg
│   ├── pic-person-02.jpg
│   ├── pic-person-03.jpg
│   ├── pic-work-01.jpg
│   ├── pic-work-02.jpg
│   └── pic-work-03.jpg
├── .gitignore
├── index.html
├── README.md
└── LICENSE (if present in your repo)
```

## Getting Started

Since this is a static website, you do not need a build tool or package installation.

### Option 1: Open directly in a browser

1. Clone the repository.
2. Open `index.html` in your browser.

### Option 2: Serve locally

From the project root, run:

```bash
python3 -m http.server 8000
```

Then open:

```bash
http://localhost:8000
```

## Notes

- The project uses a simple static HTML/CSS architecture.
- Styling is defined in `CSS_advanced/style.css`.
- Fonts and CSS resets are loaded from external CDNs.
- The page is designed as a marketing homepage and is best suited for static previews or educational front-end practice.

## License

This project does not currently declare a specific license in the README. If you intend to publish or distribute it publicly, consider adding an appropriate open-source license such as MIT.
