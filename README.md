# Personal Portfolio Website — College HTML5 & CSS3 Project

A modern, responsive, and beginner-friendly **Personal Portfolio Website** built using pure **HTML5** and **CSS3** (with zero CSS frameworks and zero unnecessary JavaScript). Designed for a 1st-year B.Tech Computer Science & Engineering student to showcase skills, academic background, projects, achievements, and contact details.

---

## Project File Structure

```text
personal-portfolio-website/
├── index.html
├── style.css
├── README.md
└── assets/
    └── images/
        ├── hero-portrait.png
        ├── about-workspace.png
        ├── project-campus.png
        ├── project-planner.png
        ├── project-dsa.png
        └── project-ecotrack.png
```

---

## Features Implemented

- **Sticky Glassmorphic Navbar & Pure-CSS Mobile Menu**: Smooth anchor scrolling (`scroll-behavior: smooth`) with a responsive hamburger drawer powered purely by CSS (`:checked`).
- **Hero Section (`#home`)**: Display typography, status badge, call-to-action buttons, highlight metrics, and framed student portrait with floating tech badges.
- **About Me (`#about`)**: Student bio, workspace showcase image, key academic info grid, and direct collaboration links.
- **Skills (`#skills`)**: Categorized skill cards (Frontend, Programming Foundations, Tools) with custom progress bars and learning tags.
- **Projects (`#projects`)**: Four project cards with hover image zoom, tech tags, GitHub links, and pure-CSS `:target` detail preview modals.
- **Education (`#education`)**: Vertical academic timeline covering B.Tech CSE (1st Year), Class XII, and Class X.
- **Achievements (`#achievements`)**: Clean milestone cards for hackathons, design sprints, certifications, and coding practice.
- **Contact (`#contact`) & Footer**: Direct email (`mailto:`), social links, accessible HTML5 validated contact form, and quick footer navigation with a Back-to-Top button.
- **Fully Responsive**: Tested across desktop, tablet (`<= 992px`), and mobile (`<= 768px` / `<= 480px`) viewports without horizontal scrolling.

---

## Technologies Used

- **HTML5** (Semantic structure: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`)
- **CSS3** (Custom Properties, Flexbox, CSS Grid, Media Queries, Transitions, `:target` modals)
- **Google Fonts** (`Plus Jakarta Sans`, `Inter`, `JetBrains Mono`)
- **Font Awesome 6 Free** (CDN icons)

---

## How to Run the Website Using VS Code Live Server

1. **Open the Project Folder in VS Code**
   - Launch **Visual Studio Code**.
   - Click **File > Open Folder...** and select the `personal-portfolio-website` folder.

2. **Install the Live Server Extension** *(if not already installed)*
   - Open the **Extensions** panel (`Ctrl + Shift + X` on Windows/Linux or `Cmd + Shift + X` on macOS).
   - Search for **`Live Server`** (by *Ritwick Dey*) and click **Install**.

3. **Launch the Website**
   - Open `index.html` in the VS Code editor.
   - Click **"Go Live"** in the bottom-right status bar (or right-click inside `index.html` and choose **"Open with Live Server"**).
   - Your default browser will open automatically at `http://127.0.0.1:5500/index.html`.

4. **Customize for Yourself**
   - Edit your name, college name, email (`aarav.sharma@example.com`), and GitHub/LinkedIn URLs in `index.html`.
   - Adjust theme colors anytime inside the `:root` variables at the top of `style.css`.
