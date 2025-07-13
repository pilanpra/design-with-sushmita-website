# Design with Sushmita Website

**Tech stack:** React (Create React App) + React Router + Tailwind CSS  
**Deployment:** Netlify (via GitHub Actions)

## Setup (Local)
1. `git clone <repo-url>`
2. `cd design-with-sushmita-website`
3. `npm install`
4. `npm start`  // http://localhost:3000

## Build & Deploy
- Configure GitHub secrets: `NETLIFY_AUTH_TOKEN`, `NETLIFY_SITE_ID`
- Push to `main` branch → auto-deploy on Netlify.

## Swap Calendly Link
- In `src/pages/Booking.js`, replace `CALENDLY_PLACEHOLDER_LINK` with your actual Calendly URL.

## Features
- Responsive layout (mobile & desktop)
- Dark & light mode (toggle via `className` on `<html>`)
- SEO-ready meta tags in `public/index.html`
