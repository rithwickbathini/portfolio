# Rithwick Bathini — Personal Portfolio

Live site: **[rithwickbathini.github.io/portfolio](https://rithwickbathini.github.io/portfolio/)**

A cinematic, Awwwards-inspired personal portfolio built as a single self-contained HTML file. No frameworks, no build tools — pure HTML, CSS, and JavaScript.

---

## About

This portfolio showcases my work as a Software Engineer and AI Developer based in Hyderabad, India. It is designed to feel like a high-end agency website with scroll-driven storytelling, editorial typography, and layered motion effects.

---

## Features

- **Horizontal sticky project scroll** — projects scroll horizontally as the user scrolls vertically, with spring-lerp physics for a Framer Motion quality feel
- **Parallax photo** — profile image drifts at a different rate than surrounding content
- **Animated gradient blobs** — soft radial orbs drift and breathe in the hero background
- **Editorial typography** — Playfair Display serif headings up to 14vw, mixing upright and italic weights
- **Scroll reveal animations** — elements enter from left, right, or bottom depending on their position, with staggered delays
- **3D card tilt** — all cards respond to mouse position with live perspective transforms
- **Premium skill cards** — glass morphism with shimmer sweep, top-edge glow, and lift on hover
- **Typewriter effect** — cycles through four role titles with smooth delete and retype
- **Animated counters** — stats count up with an easing curve on scroll into view
- **Scroll progress bar** — 2px blue gradient line at the top of the viewport
- **Scroll dot indicator** — pill-shaped active indicator on the right side
- **Dark marquee strip** — italic serif text scrolls between the hero and about sections
- **Certifications marquee** — auto-scrolling badge track that pauses on hover
- **Contact form** — client-side validation with a success toast notification

---

## Sections

| Section | Description |
|---|---|
| Hero | Full-screen with large editorial name, typewriter subtitle, floating stat cards, animated blobs |
| About | Split layout — parallax profile photo with overlay badge, text with highlighted keywords |
| Projects | Horizontal sticky scroll with 4 large project cards |
| Skills | Light glass cards with shimmer, glow, and ambient orbs in the background |
| Experience | Animated timeline — CloudEon Tech (Engineer), CloudEon Tech (Intern), Parul University |
| Certifications | Auto-scrolling marquee of credential badges |
| Testimonials | 3 quote cards on dark background |
| Contact | Split layout — contact info + message form |

---

## Projects Showcased

1. **ServiceNow Attachment Downloader** — Python enterprise tool for bulk attachment downloads with pagination and retry logic
2. **Restaurant Voice AI Bot** — Real-time conversational phone bot using Deepgram, OpenAI, and Twilio via FastAPI
3. **Retail Sales Analytics Platform** — 500K+ record pipeline with Python/SQL and Power BI dashboards
4. **Customer Churn Prediction Model** — ML classifier with EDA, feature engineering, and retention insights

---

## Tech Stack (Portfolio)

- HTML5, CSS3 (custom properties, backdrop-filter, conic-gradient, clip-path)
- Vanilla JavaScript (IntersectionObserver, requestAnimationFrame, lerp scroll)
- Google Fonts — Playfair Display, Inter, JetBrains Mono
- Hosted on GitHub Pages

---

## Local Development

No build step required. Open directly in a browser:

```bash
git clone https://github.com/rithwickbathini/portfolio.git
cd portfolio
# Open index.html in your browser
start index.html        # Windows
open index.html         # macOS
```

---

## Deployment

The site is hosted on **GitHub Pages** from the `main` branch root. Every push to `main` automatically updates the live site within ~1 minute.

To enable GitHub Pages on a fork:
1. Go to **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / folder: **/ (root)**
4. Save — live at `https://<your-username>.github.io/portfolio/`

---

## Author

**Rithwick Bathini**
Software Engineer & AI Developer · Hyderabad, India

- Email: rithwickbathini@gmail.com
- LinkedIn: [linkedin.com/in/rithwickbathini](https://linkedin.com/in/rithwickbathini)
- GitHub: [github.com/rithwickbathini](https://github.com/rithwickbathini)
