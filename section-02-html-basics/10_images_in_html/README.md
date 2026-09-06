# 📄 10 — Images in HTML

## 🧭 What this lesson covers
The `<img>` tag — embedding images, why it's self-closing, and the core attributes that control what's shown and displayed size.

## 📁 File
[`images.html`](./images.html)

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — contains only a `<title>` (no charset or viewport meta tags yet)
-  `<body>`
  -  `<h1>` — page heading: "Images"
  -  Explanation that `<img>` inserts images and is self-closing (no closing tag needed)
  -  Two `<img>` elements pulling photos from Pexels, each with `src`, `alt`, and `width` set

## 🔑 Key concepts introduced
-  `<img>` — the image embedding tag
-  Self-closing tags — `<img>` needs no `</img>`
-  `src` attribute — where the image comes from
-  `alt` attribute — fallback text for accessibility / when the image fails to load
-  `width` attribute — controls the rendered display size

## 🚧 Not yet covered here
-  `<meta charset="UTF-8">` / viewport meta tags
-  Hotlinking risk — the images are loaded from Pexels URLs containing session/tracking query parameters (`_ga`, `_gl`), which are likely temporary and could break later; safer practice is downloading images and hosting them locally in the repo
-  Pairing `height` with `width` (or using CSS `aspect-ratio`) to prevent layout shift while the image loads
-  `<figure>` / `<figcaption>` for captioned images
-  `srcset` / responsive images for different screen sizes

## ▶️ How to view
Open `images.html` directly in any browser — no build step or dependencies required. Requires an internet connection since the images are hotlinked, not stored locally. 🌍
