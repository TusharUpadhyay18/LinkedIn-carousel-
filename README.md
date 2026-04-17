# Tushar Upadhyay — Futuristic Portfolio Website

A single-file, fully editable personal portfolio website with a futuristic cyberpunk aesthetic. No frameworks, no build tools — just open `portfolio.html` in any browser.

---

## Preview

- Animated particle + grid background
- Neon cyan/purple/pink color scheme
- Glassmorphism cards with glow hover effects
- Typing animation cycling through your roles
- Scroll-reveal animations on every section
- Built-in **Edit Mode** — edit everything visually in the browser

---

## Getting Started

### Open Locally

Double-click `portfolio.html` or paste this into your browser:

```
file:///C:/Users/tusha/OneDrive/Desktop/Projects/portfolio.html
```

No installation. No dependencies. Works offline.

---

## Edit Mode — How to Use

Everything on the portfolio is editable directly in the browser — no code required.

### Step 1 — Enter Edit Mode
Click the **"Edit Mode"** button at the bottom-right corner of the screen.
A pink banner appears at the top confirming you are in edit mode.

### Step 2 — Edit Your Content
Click on any text to edit it inline:

| What to edit | How |
|---|---|
| Name, bio, titles | Click the text and type |
| Profile photo | Click the profile circle → Upload image |
| Skill tags | Click `✕` to remove · Click `+ Add Skill` to add |
| Experience entries | Click `✕ Remove` to delete · Click `+ Add Experience` to add new |
| Projects | Click `✕ Remove` to delete · Click `+ Add Project` to add new |
| Education | Click `✕ Remove` to delete · Click `+ Add Education` to add new |
| Certifications | Click `✕` to delete · Click `+ Add Certification` to add new |
| Links (GitHub, email, etc.) | Click any link button → popup editor appears |
| Contact links | Click `+ Add Contact Link` to add new |

### Step 3 — Save Your Changes
Click the green **"Save File"** button.
Your browser downloads an updated `portfolio.html` with all your changes saved.
Replace the old file with the downloaded one.

> **Tip:** Each time you make changes, click Save File to download the latest version.

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Your name, animated role titles, and a short bio |
| **About** | Profile photo, bio paragraphs, and key stats |
| **Skills** | Tech stack organized by category (Languages, Frameworks, etc.) |
| **Experience** | Timeline of work history |
| **Projects** | Featured project cards with tech stack and links |
| **Education** | Degree cards and certification badges |
| **Contact** | Social/contact links |

---

## Customization (Optional — for developers)

If you want to go beyond Edit Mode and tweak the design, open `portfolio.html` in any code editor.

### Change Colors
Edit the CSS variables at the top of the `<style>` block:

```css
:root {
  --cyan:   #00f5ff;   /* Primary accent */
  --purple: #9b59ff;   /* Secondary accent */
  --pink:   #ff2d78;   /* Highlight / edit mode */
  --dark:   #04060f;   /* Background */
}
```

### Change Typed Titles
Find the `titles` array in the `<script>` block:

```js
const titles = [
  "Software Developer",
  "Full Stack Engineer",
  "Problem Solver",
  "Tech Enthusiast"
];
```

### Add/Remove Nav Links
Find the `<ul class="nav-links">` block in the HTML and edit the `<li>` items.

---

## Deployment — Get a Public Link

| Platform | Steps | Cost |
|---|---|---|
| **Netlify** | Go to netlify.com → drag & drop `portfolio.html` → instant URL | Free |
| **GitHub Pages** | Push to a GitHub repo → Settings → Pages → Enable | Free |
| **Vercel** | vercel.com → import repo or upload file → live URL | Free |

**Netlify** is the fastest — drag and drop, done in under 60 seconds.

---

## File Structure

```
Projects/
└── portfolio.html    # The entire website — one self-contained file
└── README.md         # This file
```

---

## Tech Stack

- **HTML5** — Structure
- **CSS3** — Glassmorphism, animations, CSS variables
- **Vanilla JavaScript** — Particle canvas, typed animation, Edit Mode engine
- **Google Fonts** — Orbitron, Rajdhani, JetBrains Mono
- **Font Awesome 6** — Icons

No npm. No build step. No frameworks.

---

## License

Personal use. Built for Tushar Upadhyay's portfolio.
