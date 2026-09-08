# 📄 18 — iFrames and Embedding Content

## 🧭 What this lesson covers
Embedding external content — your own live portfolio and a YouTube video — inside the current page using `<iframe>`, plus a reference table of common iframe attributes.

## 📁 File
[`iframes.html`](./iframes.html)

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — contains only a `<title>` (no charset or viewport meta tags yet)
-  `<body>`
-  `<h1>` — page heading: "Iframes and Embedding Content"
-  A live `<iframe>` embedding the actual deployed portfolio site (`tirth-1110.github.io`)
-  A second `<iframe>` embedding a YouTube video with `allowfullscreen` attribute
-  A reference **table** listing key iframe attributes (`src`, `width`/`height`, `frameborder`, `allowfullscreen`, `loading="lazy"`)
-  A closing security note about `X-Frame-Options`

## 🔑 Key concepts introduced
-  `<iframe src="...">` — embeds another page or resource inside the current one
-  `width` / `height` — sizing the embedded frame
-  `allowfullscreen` — lets embedded video expand to fullscreen
-  Security awareness — some sites block being iframed via the `X-Frame-Options` HTTP header

## 🚧 Not yet covered here
-  `<meta charset="UTF-8">` / viewport meta tags
-  **Deprecated attribute**: `frameborder="0"` is old HTML — the modern equivalent is CSS (`border: none`)
-  `sandbox` attribute — restricts what embedded content is allowed to do (extra security layer beyond `allow`)
-  Responsive iframes (fixed pixel `width`/`height` here won't scale on smaller screens without CSS)

## ▶️ How to view
Open `iframes.html` directly in any browser. Both iframes require an internet connection — one loads your live portfolio, the other loads a real YouTube video. 🌍