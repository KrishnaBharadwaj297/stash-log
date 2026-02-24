<div align="center">
  <img src="assets/logo.png" alt="Stash Logo" width="120" />
  <h1>Stash</h1>
  <p><em>Your Personal Knowledge Logbook</em></p>
</div>

![Stash App Demo](assets/demo.webp)

## Overview
Stash is a lightweight, local-first web application designed to help you curate, understand, and retain knowledge from various sources around the web. Built with a beautiful dark-mode interface and focusing on high utility, Stash is perfect for keeping track of interesting links, tweets, books, and GitHub repositories without losing them in a sea of browser bookmarks.

## Features

- **Multi-Source Tracking**: Categorize your curated knowledge by source (X/Twitter, Reddit, GitHub, Books/PDFs, and general Links).
- **Spaced Repetition & Revisit Queue**: Never forget what you learned. Set customized revisiting intervals (Tomorrow, 3 days, 1 week, etc.) to actively review items when they are due.
- **Auto-Detection**: Simply paste a URL (like `github.com/...` or `x.com/...`) and Stash automatically categorizes the item type.
- **Smart Metadata & Progress tracking**: 
  - Track your **understanding progress** of complex repositories (like GitHub projects) via an interactive slider.
  - Add highlights from books or PDF excerpts.
  - Tag system with an auto-generated tag cloud to quickly filter your stashed items.
- **Keyboard Friendly**: Hit `Cmd+K` (or `Ctrl+K`) anywhere to quickly stash a new piece of knowledge.
- **Privacy First**: Everything is stored directly in your browser's `localStorage`. No accounts, no data leaving your machine, no databases to set up.

## Getting Started

Since Stash is a purely client-side HTML application, you can run it instantly without any build steps or server requirements!

1. Clone or download this repository.
2. Open `stash.html` directly in your favorite modern browser (e.g., Chrome, Firefox, Safari, Arc).
3. Start stashing!

## Technologies Used

- **Vanilla HTML / CSS / JavaScript**: Zero external dependencies and extremely fast.
- **CSS Variables**: Theming is fully customizable via root CSS variables.
- **Web Storage API**: `localStorage` handles all data persistence effortlessly across browser reloads.
- **Google Fonts**: Uses 'IBM Plex Mono' and 'Fraunces' for an elegant typography mix.

## Customization

Stash's design system is modular. You can easily tweak the look and feel in the `:root` styles section within the `<style>` block in `stash.html`:

```css
:root {
  --bg: #0e0f0e;
  --text: #d4d3c8;
  --accent: #c8f060; /* Change this for a new primary flavor! */
  --surface: #161714;
  /* ... */
}
```
