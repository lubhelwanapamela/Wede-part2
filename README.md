# Campus Connect

Campus Connect is a student-focused website that brings academic support, study resources, campus events and wellbeing information into one place, so students don't have to search across multiple sites and social media pages to find what they need.

This repository contains the redesigned front-end for the Campus Connect website, built for the WEDE5020 website proposal.

## Live structure

| Page | File | Purpose |
|---|---|---|
| Home | `index.html` | Overview of what Campus Connect offers, key stats and quick links |
| About | `about.html` | Mission, vision, target audience and the redesign story |
| Resources | `resources.html` | Academic support, events and wellbeing resources, plus an FAQ |
| Contact | `contact.html` | Contact form and direct contact details |

Shared assets:
- `css/style.css` — colour palette, layout, components and animations
- `js/script.js` — navigation, scroll reveal, counters, FAQ accordion and form handling

## Design

- **Colour palette:** navy (`#0f2545`), blue (`#1d4ed8`), sky (`#38bdf8`) and light grey (`#f6f8fb`), chosen to feel trustworthy, clean and easy to read.
- **Typography:** Poppins, with a system-font fallback stack.
- **Motion:** scroll-triggered reveal animations, animated counters and progress bars, a floating hero illustration, hover transitions on cards and buttons, and a smooth mobile navigation drawer. All animations are built with CSS keyframes/transitions and the `IntersectionObserver` API — no external animation libraries are required.
- **Responsiveness:** layouts adapt for desktop, tablet and mobile, with a collapsible navigation menu below 720px.

## Technologies used

- HTML5 for page structure
- CSS3 for styling, layout (Flexbox/Grid) and animation
- Vanilla JavaScript for interactivity (no frameworks or build step required)
- Google Fonts (Poppins)

## Running the site locally

No build step is required. Open `index.html` in a browser, or serve the folder with any static file server, for example:

```
python -m http.server 8000
```

then visit `http://localhost:8000`.

## Deployment

The site is a static HTML/CSS/JS project, so it can be hosted on any static hosting service, including GitHub Pages, without additional server-side setup.

## References

CJX Studios (2026) *How much does it cost to register a website in South Africa?* Available at: https://cjxstudio.co.za/website-registration-cost-south-africa-2026 (Accessed: 14 August 2026).

GitHub (2026) *About custom domains and GitHub Pages*. Available at: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages (Accessed: 14 August 2026).

GitHub (2026) *GitHub Pages documentation*. Available at: https://docs.github.com/en/pages (Accessed: 14 August 2026).

GitHub (2026) *GitHub Pages limits*. Available at: https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits (Accessed: 14 August 2026).

Google Fonts (n.d.) *Poppins*. Available at: https://fonts.google.com/specimen/Poppins (Accessed: 14 August 2026).

MDN Web Docs (n.d.) *Intersection Observer API*. Mozilla. Available at: https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API (Accessed: 14 August 2026).

MDN Web Docs (n.d.) *CSS animations*. Mozilla. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animations (Accessed: 14 August 2026).

W3Schools (n.d.) *HTML, CSS and JavaScript tutorials*. Available at: https://www.w3schools.com (Accessed: 14 August 2026).

## Author

Noxolo Pamella Lubhelwana
