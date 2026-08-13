# Thorne & Co. Plumbing Services — Website

WEDE5020 – Web Development
Part 1: Building the Foundation — Project Initiation and Planning

## About This Project

This is a static, multi-page website built for the **Thorne & Co. Plumbing Services** proposal (Proposal 1). It follows the sitemap, colour scheme, typography, and feature list set out in the project proposal document.

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Hero banner, service highlights, testimonials |
| About Us | `about.html` | Company history, mission/vision, team profiles |
| Services | `services.html` | Full list of services offered |
| Gallery | `gallery.html` | Filterable before/after job photos |
| Contact | `contact.html` | Enquiry form, map, phone/WhatsApp links, service areas |

## Folder Structure

```
thorne-co/
├── index.html
├── about.html
├── services.html
├── gallery.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── images/
    └── (placeholder photos — replace with real ones)
```

## Tech Used

- **HTML5** for page structure
- **CSS3** for styling and responsive (mobile-first) layout
- **JavaScript (vanilla)** for:
  - mobile navigation toggle
  - contact form validation
  - gallery filter buttons
- **Google Fonts** — Montserrat (headings) and Open Sans (body text)

No frameworks, build tools, or backend are used — this is a static site, in line with the proposal's technical requirements.

## How to View It

1. Unzip/download the `thorne-co` folder.
2. Open `index.html` directly in a browser, **or**
3. Open the folder in VS Code and run it with the **Live Server** extension for the best experience (so relative links and the sticky nav work as intended).

## Design Reference

- **Colours:** Deep Navy `#1B3A5C`, Copper Accent `#C97B3D`, Light Grey `#F2F2F2`, White `#FFFFFF`
- **Fonts:** Montserrat Bold (headings), Open Sans Regular (body)
- Layout follows the low-fidelity wireframe and sitemap included in the proposal.

## Notes

- Images in `images/` are placeholders generated for this build — swap them out for real photos of the business, team, and completed jobs before using this live.
- The enquiry form validates input but does not submit anywhere (no backend), which is expected for a static HTML/CSS/JS assignment.
- `thorne-co-content-research.md` (in the parent folder) documents the research used to sense-check pricing, hosting costs, and South African plumbing industry/compliance details (PIRB registration, POPIA) that informed some of the content on this site.

## Author

[Your Full Name] — [Your Student Number]
