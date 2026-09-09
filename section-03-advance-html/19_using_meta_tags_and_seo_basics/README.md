# 📄 19 — Using Meta Tags and SEO Basics

## 🧭 What this lesson covers
The `<meta>` tags that live in `<head>` (charset, description, keywords, viewport, author) and the core SEO practices they support.

## 📁 File
[`meta.html`](./meta.html)

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — this time actually populated: `charset`, `viewport`, `description`, `keywords`, `author`, and `title`
-  `<body>`
-  **Meta Tags** section — explanation + a list covering charset, description, keywords, viewport, author, and refresh meta tags
-  **SEO Basics** section — explanation + a list covering title tags, meta description, header tags, semantic HTML, and the viewport tag

## 🔑 Key concepts introduced
-  `<meta charset="UTF-8">` — finally appears in a lesson file, after being flagged as missing in nearly every prior one
-  `<meta name="description" content="...">` — summary shown in search engine results
-  `<meta name="keywords" content="...">` — largely ignored by modern search engines, noted honestly in the lesson itself
-  `<meta name="viewport" content="...">` — controls mobile responsiveness
-  `<meta name="author" content="...">` — declares page authorship
-  `<meta http-equiv="refresh">` — auto-refresh/redirect (mentioned, not demonstrated)
-  SEO fundamentals: descriptive `<title>`, meaningful heading hierarchy, semantic HTML, and the viewport tag's role in mobile SEO

## 🚧 Not yet covered here
-  Open Graph meta tags (`og:title`, `og:image`, etc.) for how links preview on social media
-  `<link rel="canonical">` for SEO duplicate-content handling
-  Actually demonstrating `meta http-equiv="refresh"` in code, rather than just describing it

## ▶️ How to view
Open `meta.html` directly in any browser — no build step or dependencies required. Meta tags themselves aren't visible on the page; view via "View Page Source" or DevTools to see them in the `<head>`. 🌍