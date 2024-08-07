# Travel Site

A responsive travel website showcasing curated destinations — Hawaii, Iceland, and Greece — with itineraries, a recommendations gallery, and a contact footer.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

## Features

- Responsive layout — mobile, tablet, and desktop breakpoints
- Destination gallery with hover animations
- Per-destination itinerary pages (Hawaii, Iceland, Greece)
- Clean footer with contact info, business hours, and social links
- No build step — pure HTML/CSS, open in any browser

## Structure

```
Travel-Site/
├── index.html          # Home page
├── pages/
│   ├── hawaii.html     # Hawaii destination + itinerary
│   ├── iceland.html    # Iceland destination + itinerary
│   └── greece.html     # Greece destination + itinerary
├── css/
│   ├── global.css      # Shared nav and link styles
│   ├── main.css        # Layout, hero, recommendations, footer
│   └── destination.css # Destination page specific styles
└── assests/
    ├── images/         # Hero and destination images
    └── Icons/          # Social media icons
```

## Setup

No dependencies. Just open `index.html` in a browser:

```bash
git clone https://github.com/NadirAliOfficial/Travel-Site.git
cd Travel-Site
open index.html
```

Or use Live Server in VS Code for hot reload.

## Color Palette

| Role       | Color     |
|------------|-----------|
| Primary    | `#335576` |
| Accent     | `#db7a4e` |
| Background | `#fefaf5` |

## License

MIT
<!-- updated: 2026-06-17 -->

