# Barista Toolkit

A lightweight, bilingual (English / Arabic) barista workspace designed to run as a static GitHub Pages site.

## Features
- Espresso ratio calculator with shot-style classification and target yield.
- Brew calculator for V60, French Press and Cold Brew ratios.
- Recipe scaler with editable ingredients and serving multiplier.
- Coffee bean log for origin, process, roast level and tasting notes.
- English / Arabic interface with automatic RTL layout.
- Responsive light theme; saved recipes and bean notes stay in the browser using localStorage.

## Run locally
Open `index.html` in a modern browser. No build step or external dependencies are required.

## Publish with GitHub Pages
1. Open the repository on GitHub.
2. Choose **Add file → Upload files**.
3. Upload `index.html` and `README.md` from this project folder (replace the existing files if prompted).
4. Commit to the `main` branch.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Choose branch `main`, folder `/ (root)`, then **Save**.
8. Wait for the deployment to finish. The site URL is usually `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Data note
Saved recipes and coffee logs are stored locally in the browser on the device where they were entered. They are not synchronized between devices and may be cleared if browser data is deleted.
