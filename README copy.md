# Lee Sangoroh Portfolio Website

A clean, Apple-inspired, mobile-friendly portfolio website built with plain HTML, CSS, and JavaScript.

## Pages

- `index.html` — Home page
- `work.html` — Work experience and portfolio projects
- `influences.html` — Books, people, and ideas shaping your thinking
- `contact.html` — Contact page with placeholder links and form

## Design Choices

- Style: Apple-native minimalism
- Font: Inter with system fallback
- Accent: `#007AFF`
- Background: `#F9F9FB`
- Cards: white/dark surface, subtle border, soft radius
- Mobile: responsive layout and mobile navigation
- Accessibility: semantic HTML, skip link, visible labels, large buttons, alt text placeholders
- Dark Mode: manual toggle with local storage

## Placeholders to Replace

1. Replace `assets/profile-placeholder.svg` with your real professional photo.
2. Add your CV file to `assets/` and update the `Download CV` link in `index.html`.
3. Replace social links in `contact.html`:
   - Email
   - LinkedIn
   - GitHub
4. Replace project placeholders in `work.html` with your real links, demos, screenshots, and case studies.
5. Add real books and people to `influences.html`.
6. Connect the contact form to Formspree, Netlify Forms, or a custom backend.

## Running Locally

Open `index.html` in your browser.

For a better local development setup, use VS Code Live Server.

## Hosting on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders in this project.
3. Go to repository Settings.
4. Open Pages.
5. Set the source branch to `main` and folder to `/root`.
6. Save and wait for GitHub Pages to publish the site.

## File Structure

```txt
portfolio_website/
├── index.html
├── work.html
├── influences.html
├── contact.html
├── README.md
├── assets/
│   ├── favicon.svg
│   └── profile-placeholder.svg
├── css/
│   └── styles.css
└── js/
    └── main.js
```
