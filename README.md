# Liza Moeun Portfolio 2026

A retro-inspired personal portfolio for Liza Moeun, built as a responsive static website with HTML, Tailwind CSS, and Google Fonts.

## Features

- Responsive portfolio layout for desktop and mobile
- Retro operating-system visual style
- About, skills, projects, and contact sections
- Email contact links using `mailto:`
- No backend or database required

## Run Locally

Open `index.html` directly in a browser, or serve the folder with a local web server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Build Styles

Tailwind CSS is compiled locally for production and served from `styles.css`. After changing Tailwind classes, regenerate the stylesheet with:

```bash
npm install
npm run build:css
```

Commit the regenerated `styles.css` with your changes so static hosting can serve the site without a build step.
