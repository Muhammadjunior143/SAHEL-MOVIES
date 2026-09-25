# SAHEL MOVIES

SAHEL MOVIES is a cinematic, single-page streaming and CMS website built for VJ Luganda content, with a glassmorphism interface and client-side movie catalog experience.

## Project structure

- `index.html` — main website entry page
- `render.yaml` — Render static site configuration
- `readme.txt` — original project notes
- `404.html` — fallback page for missing routes

## Features

- VJ Luganda movie catalog
- Free and VIP content sections
- Video player support for local blob uploads and embedded web streams
- Authentication modal
- Admin/CMS dashboard mockup and management tools
- Fully frontend-based static deployment

## Local preview

From the project folder:

```powershell
cd "C:\Users\SAHEL WA SHADIE\Desktop\SAHEL MOVIES"
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/index.html
```

## Deploy to Render

1. Push this folder to GitHub.
2. Open Render and create a new Static Site.
3. Connect the GitHub repository.
4. Set:
   - Build Command: leave empty
   - Publish Directory: .
5. Deploy.

## Notes

This project is a static frontend website. It does not require a backend or build step for Render hosting.
