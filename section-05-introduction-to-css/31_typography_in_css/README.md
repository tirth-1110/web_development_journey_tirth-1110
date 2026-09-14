# 📄 31 — Typography in CSS

## 🧭 What this lesson covers
Every core text-styling property in CSS — font, weight, style, alignment, spacing, transformation, decoration — plus how to load and use a custom Google Font.

## 📁 Files
- [`typography.html`](./typography.html)
- [`style.css`](./style.css)

## 🏗️ Structure
-  `<!DOCTYPE html>`, `<html lang="en">`, and a properly filled `<head>` (`charset`, `viewport`, `title`, linked `style.css`, plus Google Fonts `preconnect`/stylesheet links)
-  `<body>`
-  **Basic Text Properties** — an ordered list covering `font-family`, `font-size`, `font-weight`, `font-style`, `text-align`, `line-height`, `letter-spacing`, `word-spacing`, `text-transform`, and `text-decoration`, each with an explanation and a live CSS example
-  A dedicated **Common font stacks** callout showing real fallback chains (`"Helvetica Neue", Helvetica, Arial, sans-serif`, etc.)
-  **Using Google Fonts** — shows the actual `<link>` tags needed in `<head>` and the matching `font-family` CSS to apply a loaded Google Font ("Caacupe One")
-  `style.css` applies a shared `orange` background to every property example for visual demonstration

## 🔑 Key concepts introduced
-  `font-family` — typeface + fallback stack, always ending in a generic family (`sans-serif`, `serif`, `monospace`)
-  `font-size` — text size, in any CSS unit (`px`, `em`, `%`, `rem`)
-  `font-weight` — boldness, via keywords (`bold`, `lighter`) or numeric values (`100`-`900`)
-  `font-style` — `normal`, `italic`, or `oblique`
-  `text-align` — `left`, `right`, `center`, `justify`
-  `line-height` — vertical spacing between lines of text
-  `letter-spacing` / `word-spacing` — horizontal spacing between characters/words
-  `text-transform` — `uppercase`, `lowercase`, `capitalize`
-  `text-decoration` — underline, overline, line-through
-  Loading a Google Font via `<link rel="preconnect">` + stylesheet link, then referencing it by name in `font-family`

## 🚧 Not yet covered here
-  `font-variant` (small-caps, etc.)
-  `white-space` and `text-overflow` for handling overflowing text
-  Variable fonts and `font-display` strategies beyond the default `swap` used here

## ▶️ How to view
Open `typography.html` directly in any browser. Requires an internet connection to load the Google Font — without it, the last example will fall back to the default sans-serif. 🌍