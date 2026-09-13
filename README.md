# Forge 85

Forge 85 is a single-page fitness, nutrition, posture, and consistency tracker. It has no end-user account, paid API, or ChatGPT dependency.

## Private universal sync

The app creates one private sync link. Opening that same link on another device loads the same progress automatically. Tracker data is encrypted in the browser before it reaches account-free cloud storage; the private link contains the key and must not be shared. A local cache keeps the app usable during temporary connection problems. Export occasional backups because the free sync store can remove a namespace after 90 days without activity.

## GitHub Pages deployment

GitHub Pages publishes `index.html` from the root of the `main` branch. Any committed update to that file becomes the live app.
