# Forge 85

Forge 85 is a single-page fitness, nutrition, posture, and consistency tracker. It runs entirely in the browser with no server, account, paid API, or ChatGPT dependency.

## Privacy and storage

All weigh-ins, food entries, workouts, settings, and reflections are saved in the browser's `localStorage`. The repository never receives logged data. Data is tied to the browser and the exact GitHub Pages address, so use the app's **Export backup** feature before clearing browser data or changing devices.

## GitHub Pages deployment

The workflow in `.github/workflows/pages.yml` publishes the contents of `site/` whenever the `main` branch changes. In the repository's **Settings → Pages**, set the deployment source to **GitHub Actions** if GitHub does not select it automatically.
