# Ashton Hendrickson — Aerospace Engineering Portfolio 🚀

[![GitHub Pages Deployment](https://img.shields.io/badge/Deployment-GitHub%20Pages-success?style=flat-square&logo=github)](https://ashrick12.github.io/)
[![HTML5](https://img.shields.io/badge/HTML5-Semantic%20Markup-E34F26?style=flat-square&logo=html5&logoColor=white)](https://ashrick12.github.io/)
[![CSS3](https://img.shields.io/badge/CSS3-Custom%20Design%20System-1572B6?style=flat-square&logo=css3&logoColor=white)](https://ashrick12.github.io/)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla%20ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://ashrick12.github.io/)

The official repository for [ashrick12.github.io](https://ashrick12.github.io/), the personal engineering portfolio of **Ashton Hendrickson** — Aerospace Engineering student transferring to **Arizona State University** (Astronautics track, Expected Graduation: May 2028).

Designed as an editorial technical dossier presenting hardware prototypes, SolidWorks CAD assemblies, flight simulations, and computational tools.

[🌐 Live Website](https://ashrick12.github.io/) &bull; [💼 LinkedIn Profile](https://www.linkedin.com/in/ashton-hendrickson-55508a262) &bull; [💻 GitHub Profile](https://github.com/Ashrick12)

---

## Technical Stack & Architecture

The site is built completely dependency-free to ensure instant loading times, predictable cross-device rendering, and complete stylistic control:

- **Semantic HTML5:** Structured semantic markup with accessible landmark regions (`<nav>`, `<header>`, `<main>`, `<section>`, `<footer>`), ARIA modal dialogs, and SVG icon sets.
- **Custom CSS3 Design System:** A cohesive dark-theme engineering design system built entirely with CSS custom properties:
  - Strict typography pairing: `Inter` for body copy and UI hierarchy; `JetBrains Mono` for technical readouts, metadata tags, and code elements.
  - Responsive CSS Grid and Flexbox layouts optimized for mobile (320px+), tablet, and desktop (1024px+).
  - Subtle technical grid backdrops and restrained border contrasts (`--border-subtle`, `--border-medium`).
  - Zero heavy external CSS frameworks (no Bootstrap, Tailwind, or jQuery runtime overhead).
- **Vanilla JavaScript (ES6):**
  - Interactive full-resolution modal lightbox enabling detailed inspection of CAD assemblies, 2D ANSI drawings, and trajectory simulation plots.
  - Bot-safe email and resume request handler utilizing DOM data attributes to prevent automated web scraping while providing instant one-click `mailto:` execution.

---

## Featured Work Showcased

| Project | Discipline & Tools | Live Showcase |
| :--- | :--- | :--- |
| **Scratch-Built Sounding Rocket** | SolidWorks 3D CAD, OpenRocket Flight Sim, Bambu Lab A1 3D Printing, RP2040 Avionics | [Explore Flagship Case Study](https://ashrick12.github.io/#flagship) |
| **10-Part Parametric Desk Fan** | SolidWorks 3D CAD, Rotational Mates, Interference Checking, ANSI 2D Drawings | [View CAD Gallery](https://ashrick12.github.io/#cad-projects) |
| **Solar Systems Modeling & NPV** | MATLAB Numerical Methods, Energy Balance Modeling, 25-Year Lifecycle NPV | [View Simulation Output](https://ashrick12.github.io/#systems-software) |
| **Smart Schedule Finder** | Python, Streamlit, Google Calendar API OAuth2, Metro Route Optimization | [Inspect Application](https://ashrick12.github.io/#systems-software) |
| **Local Document OCR Pipeline** | Python, EasyOCR, Phi-4 Mini (4-bit Quantized), HIPAA-Compliant Edge AI | [Inspect Pipeline](https://ashrick12.github.io/#systems-software) |
| **Able Aerospace Job Shadow** | FAA Part 145 Exposure, FAA Form 8110-3 Review, Multi-Axis CNC Milling | [Read Overview](https://ashrick12.github.io/#industry-experience) |

---

## Repository Structure

```text
ashrick12.github.io/
├── assets/                          # High-resolution engineering media
│   ├── ashton_rocket.jpg            # Range prep & airframe staging photo
│   ├── desk_fan_front.png           # SolidWorks front orthographic CAD render
│   ├── desk_fan_iso.png             # SolidWorks isometric CAD render
│   ├── desk_fan_poster.png          # Full-size SolidWorks design poster & 2D drawings
│   ├── desk_fan_rear.png            # SolidWorks rear motor housing render
│   ├── desk_fan_side.png            # SolidWorks profile elevation CAD render
│   ├── headshot.png                 # Professional profile portrait
│   ├── matlab_solar_plot.png        # MATLAB simulation demand vs. solar generation plot
│   ├── portfolio_preview.png        # Social card / OpenGraph preview image
│   ├── rocket_avionics_haul.png     # RP2040, BMP390, MPU-6500 bench assembly hardware
│   ├── rocket_cad_exploded.png      # SolidWorks exploded assembly render
│   ├── rocket_hardware_haul.png     # Recovery & launch ground support equipment
│   ├── rocket_launch.gif            # Subscale test flight launch gif
│   ├── rocket_launch_far.gif        # High-altitude tracking footage
│   ├── rocket_openrocket_model.png  # OpenRocket 1.49 cal static stability model
│   ├── rocket_payload_cad.png       # SolidWorks payload bay & shock cord anchor CAD
│   ├── rocket_printed_parts.jpg     # Bambu Lab A1 3D-printed nose cone and bay
│   ├── rocket_trajectory_plot.png   # OpenRocket altitude & velocity decay curves
│   └── schedule_finder_ui.png       # Streamlit desktop application interface
├── index.html                       # Semantic single-page portfolio layout
├── styles.css                       # Complete CSS design system & responsive styling
├── portfolio.md                     # Comprehensive technical case study dossier
├── PROFILE_README.md                # GitHub user profile README for @Ashrick12
└── README.md                        # Repository documentation and setup guide
```

---

## Local Development & Preview

Because this project uses vanilla web standards with no compilation or build steps, it can be previewed locally using any static file server:

### Python 3 (Built-in)
```bash
# Navigate to the repository directory
cd ashrick12.github.io

# Start a local HTTP server on port 8000
python -m http.server 8000
```
Open your browser and navigate to `http://localhost:8000`.

### Node.js (`npx serve`)
```bash
npx serve .
```

### VS Code Live Server
1. Install the **Live Server** extension (`ritwickdey.liveserver`).
2. Right-click `index.html` and click **Open with Live Server**.

---

## Deployment

The website is continuously deployed through **GitHub Pages**. Any changes pushed or merged into the `main` branch are automatically built and published live to:

**[https://ashrick12.github.io/](https://ashrick12.github.io/)**

---

## Contact & Connect

- **Portfolio:** [ashrick12.github.io](https://ashrick12.github.io/)
- **LinkedIn:** [linkedin.com/in/ashton-hendrickson-55508a262](https://www.linkedin.com/in/ashton-hendrickson-55508a262)
- **GitHub:** [github.com/Ashrick12](https://github.com/Ashrick12)
- **Email:** Direct contact and full engineering resume available via the [portfolio contact button](https://ashrick12.github.io/#contact) or [ashtonh1204@gmail.com](mailto:ashtonh1204@gmail.com).
