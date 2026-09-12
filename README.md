# 2K Grind Service

Static website for the 2K Grind Service, including NBA 2K27 REP progression prices, additional services, and pricing notes.

## Project Structure

- `index.html` - Main pricing page
- `css/styles.css` - Site styles
- `archive/` - Archived project files and assets

## Preview Locally

Because this is a static site, no build step or package installation is required. Open `index.html` in a browser, or serve the project with any local web server:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deployment

The repository is structured for GitHub Pages. Push changes to the configured branch and GitHub Pages will serve `index.html` as the site entry point.