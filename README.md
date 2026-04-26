# Desire Incarnate

Mobile-first card battler prototype based on the generated battle mockup.

## Play

Open `web/index.html` from a hosted static server or use the GitHub Pages workflow in this repo.

## Android

This repo also contains a minimal native Android WebView wrapper that loads the same `web/index.html` game, forces landscape, and uses immersive fullscreen. The `Build Android APK` GitHub Actions workflow builds a debug APK and uploads it as an artifact.

## Current prototype

- Pure HTML/CSS/JS mobile-first game UI.
- Extracted sprites from the initial generated image: Aurelius, Cassian, and Desire Incarnate.
- Two heroes with four large cards each.
- Shared energy, block, agility, strength, vulnerable, weak, boss intent, Desire meter, three-floor run, relic rewards, victory/defeat loop.
