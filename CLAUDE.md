# CLAUDE.md — This Week in AI Report

## What this repo is
This is the landing page for the This Week in AI weekly report. It's a single-page HTML file (`index.html`) with a background image (`twiai-bg.png`) and an SVG asset (`Union.svg`).

## Links in the page
- https://thisweekinai.ai — main site
- https://www.youtube.com/@ThisWeekinAIPodcast — YouTube
- https://www.instagram.com/thisweekinaipodcast — Instagram
- https://www.tiktok.com/@thisweekinaipodcast — TikTok

## Coding standards
- This is a static HTML page. Do not introduce build tools, frameworks, or dependencies.
- All styles are inline or in a `<style>` block inside `index.html`. Keep it that way.
- Do not create new files unless absolutely necessary.
- When fixing UI bugs, always verify the fix visually using Playwright before opening a PR.

## How to verify changes
- Use Playwright to open `index.html` in a browser and take a screenshot before and after any change.
- Check that all four links above are reachable (200 status).

## PR guidelines
- Keep PRs small and focused on one change.
- Include a screenshot in the PR description if the change affects the visual layout.
