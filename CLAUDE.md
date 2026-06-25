# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

`railway-monitor-site` — a web application for monitoring railways. This repository is currently empty; no framework, build system, or tooling has been chosen yet.

## Tech Stack

Pure static HTML/CSS/JS — no build step, no framework. Google Fonts (Inter) loaded via CDN.

## Structure

```
index.html          — landing page
support/index.html  — support page served at /support (mailto: contact@swellsolutionstech.com)
css/style.css       — shared stylesheet (CSS custom properties, responsive)
assets/             — place logo.png / images here if needed
```

## Dev Server

Open `index.html` directly in a browser, or:

```
npx serve .
```

## Notes

- SVG logo is inline in both HTML files — no external image required
- Support CTA opens a pre-filled mailto to `contact@swellsolutionstech.com`
- Nav gains `.scrolled` class on scroll via a small inline `<script>`
