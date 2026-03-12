# Samin Saikia — Personal Portfolio

> **Live Site:** [samin-saikia.netlify.app](https://samin-saikia.netlify.app)

A fully hand-coded personal portfolio website built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies, no build tools. Just a single self-contained file that loads fast and works everywhere.


---

## Features

- **Custom cursor** with smooth lerp trail that follows mouse movement naturally
- **Twinkling star background** with randomized animation timing
- **Typewriter effect** cycling through 8 developer roles
- **Animated orbit rings** around the hero photo frame
- **Floating availability badges** with pulsing dot indicators
- **Scroll-reveal animations** using IntersectionObserver — elements animate in as you scroll
- **Scroll progress bar** at the top of the page
- **Mobile hamburger menu** with full-screen overlay nav
- **Contact form** powered by Web3Forms — works without a backend
- **Embedded PDF resume** in a browser-style frame with download button
- **SVG icons throughout** — no emoji, no icon fonts, works on Win7/IE9+

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Name, animated typewriter, orbit photo frame, CTA buttons |
| **About** | Bio, photo, stats badge (3+ yrs, 20+ projects, 10+ tech) |
| **Services** | 7 service cards: Web Dev, Software Dev, Full Stack, ML, Deep Learning, Agentic AI, Data Analysis |
| **Skills** | 20 skill chips across 4 groups: Frontend, Backend/DB, AI/ML, Tools |
| **Projects** | 6 real projects with images, descriptions, tech chips, GitHub links |
| **Resume** | Embedded PDF viewer with download and full-screen buttons |
| **Contact** | Web3Forms contact form + location and response-time details |
| **Footer** | GitHub and LinkedIn social links, nav links, copyright |

---

## Project Showcase

| Project | Category | Stack |
|---|---|---|
| [MAXUS — Jarvis-Style AI OS](https://github.com/Samin-Saikia/MAXUS-A-Jarvis-Style-AI-Operating-System) | Agentic AI | Groq, Flask, JS |
| [MAX.sys — Multi-Agent Software Builder](https://github.com/Samin-Saikia/MAX.sys-Multi-Agent-Software-Builder) | Agentic AI | Flask, Groq |
| [MAX Research — Deep Research Engine](https://github.com/Samin-Saikia/MAX-Research-Deep-Research-Intelligence-Engine) | Agentic AI | Flask, Groq, HTML |
| [Student Performance Predictor](https://github.com/Samin-Saikia/Student-Performance-Predictor) | Machine Learning | Pandas, Scikit-learn, NumPy |
| [ProductivityFlow](https://github.com/Samin-Saikia/ProductivityFlow---A-task-management-application) | Productivity Tool | HTML, CSS, JS |
| [Full-Stack Django Blog App](https://github.com/Samin-Saikia/full-stack-Django-blog-app) | Web App | Django, MySQL, HTML |

---

## Tech Stack

```
Frontend:   HTML5 · CSS3 · Vanilla JavaScript
Fonts:      Syne (display) · DM Sans (body) · JetBrains Mono (code)
Icons:      Inline SVG — no external icon library
Forms:      Web3Forms (serverless form submission)
Hosting:    Netlify
```

---

## File Structure

```
portfolio/
├── index.html                  ← Entire site (single file)
├── README.md
└── assets/
    ├── images/
    │   ├── logo.jpg            ← Navbar logo
    │   ├── me.webp             ← Hero photo
    │   ├── about.jpg           ← About section photo
    │   ├── Screenshot_7.png    ← MAXUS project image
    │   ├── Screenshot_12.png   ← MAX.sys project image
    │   ├── Screenshot_17.png   ← MAX Research project image
    │   ├── performance.webp    ← Student Predictor image
    │   ├── productivity.avif   ← ProductivityFlow image
    │   └── blog.avif           ← Django Blog image
    └── pdf/
        └── Samin_Saikia_Resume.pdf
```

---

## Customization

To update any section, open `index.html` and search for the relevant comment block:

```html
      ← name, typewriter words, CTA buttons
     ← bio paragraphs, stats numbers, tag pills
  ← service card text
    ← skill chips and their SVG icons
  ← project cards, images, GitHub links
    ← PDF file path
   ← Web3Forms access key, location text
    ← GitHub/LinkedIn URLs, copyright year
```

To update the contact form, replace the Web3Forms access key:
```html

```
Get a free key at [web3forms.com](https://web3forms.com).

---

## Deployment

The site is deployed on **Netlify**
