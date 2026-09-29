# Weekly Job Board

A responsive front-end job board that lists weekly openings from companies such as Microsoft, Morgan Stanley, Ansys, Harman, HCLTech and Zomato. Each listing shows the role, job type (full-time, part-time, internship) and salary, with an apply link.

## Features
- Job cards with company logo, role, work type and salary
- Responsive layout built on Bootstrap 4
- Scroll animations (AOS), carousels (Swiper), lightbox (Fancybox) and animated counters
- Off-canvas side menu for mobile

## Tech stack
HTML5 · CSS3 / SCSS · Bootstrap · jQuery · AOS · Swiper · Fancybox

## Run locally
It's a static site, so no build step is needed:
```bash
git clone git@github.com:agvs03/Job-Board-Main.git
cd Job-Board-Main
python -m http.server 8000
```
Then open http://localhost:8000 (or just open `index.html` in a browser).

## Deploy on GitHub Pages
Go to **Settings → Pages → Source: Deploy from a branch → `main` / root**. The site will be served at `https://agvs03.github.io/Job-Board-Main/`.

## Project structure
```
index.html
assets/
  css/   js/   fonts/   img/
  scss/        # Source styles (components, common variables & mixins)
```
