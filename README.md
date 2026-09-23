# SJMormo | Personal Portfolio

My personal portfolio website, showcasing my background, research, work experience, projects, and skills.

🌐 **Live site:** [https://sjmormo.github.io](https://sjmormo.github.io)

---

## About

I'm **Samver Jahan Mormo**, a former R&D Engineer at Shanghai BDCOM, based in Dhaka, Bangladesh. This website is a single-page portfolio that brings together my academic background, research, professional experience, and projects in one place.

## Sections

| Section | Description |
| --- | --- |
| [About](https://sjmormo.github.io/#about-section) | A short introduction and background |
| [Education](https://sjmormo.github.io/#education-section) | Academic history |
| [Research](https://sjmormo.github.io/#research-section) | Research interests and publications |
| [Job Experience](https://sjmormo.github.io/#work-section) | Professional work history |
| [Projects](https://sjmormo.github.io/#projects-section) | Selected personal and academic projects |
| [Skills](https://sjmormo.github.io/#skills-section) | Technical skills and tools |
| [Contests](https://sjmormo.github.io/#contests-section) | Competitions and achievements |
| [CV](https://sjmormo.github.io/#cv-section) | Downloadable curriculum vitae |

## Project Structure

```
sjmormo-portfolio/
├── index.html              # Main page (header, navigation, section loader)
├── about/                  # About section
├── education/
│   └── education.html      # Education section
├── research/
│   └── research.html       # Research section
├── work/
│   └── work.html           # Job experience section
├── projects/
│   └── projects.html       # Projects section
├── skills/
│   └── skills.html         # Skills section
├── contest/
│   └── contest.html        # Contests section
├── cv/
│   └── cv.html             # CV section
├── assets/
│   ├── css/
│   │   └── index.css       # Site-wide styles
│   ├── images/
│   │   ├── profile.jpg     # Profile picture
│   │   ├── profile_jpeg
│   │   └── project/        # Project screenshots
│   │       ├── hcr.png
│   │       ├── tftp.jpg
│   │       └── webpage.png
│   └── pdf/
│       └── Samver_Jahan_Mormo.pdf   # Downloadable CV
└── README.md
```

## Run Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/SJMormo/sjmormo.github.io.git
   cd sjmormo.github.io
   ```

2. **Open the site**

   Open `index.html` directly in your browser, or serve it with a local server:

   ```bash
   # Using Python
   python -m http.server 8000

   ```

3. Visit `http://localhost:8000` in your browser.