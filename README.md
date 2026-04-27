# M K Pranitha Portfolio

A personal portfolio website inspired by a clean single-page structure.

## Files

- `index.html` - main page content
- `styles.css` - visual styling and responsive design
- `script.js` - small UI helpers
- `assets/resume.pdf` - place your resume PDF here

## Run locally

Open `index.html` directly in a browser, or use a static server:

```powershell
cd "pranitha-portfolio"
python -m http.server 5500
```

Then open `http://localhost:5500`.

## Add your resume

Copy your latest PDF to:

`assets/resume.pdf`

## Host on GitHub Pages

1. Create a GitHub repository and push this project.
2. In your repository, go to **Settings -> Pages**.
3. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` and folder `/ (root)`
4. Save and wait 1-2 minutes.
5. Your live URL will be:
   `https://<your-username>.github.io/<repo-name>/`
