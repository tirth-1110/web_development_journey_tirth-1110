# 📄 16 — HTML Entities & Special Characters

## 🧭 What this lesson covers
Why certain characters can't be typed directly in HTML, and the entity codes used to display them instead.

## 📁 File
[`entities_and_special_characters.html`](./entities_and_special_characters.html)

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — contains only a `<title>` (no charset or viewport meta tags yet)
-  `<body>`
-  Intro paragraph explaining why entities exist
-  A list of common entities, each shown rendered alongside the code used to produce it
-  A closing link out to a reference site (compart.com) for the full entity list

## 🔑 Key concepts introduced
-  `&amp;` / `&lt;` / `&gt;` / `&quot;` / `&apos;` — entities for characters HTML treats specially (`&`, `<`, `>`, `"`, `'`)
-  `&copy;` / `&reg;` — copyright and registered trademark symbols
-  `&#8377;` — numeric entity for the Rupee symbol
-  `&rarr;` / `&larr;` / `&uarr;` / `&darr;` — directional arrow entities
-  `&nbsp;` — non-breaking space (prevents a line break at that point)

## 🚧 Not yet covered here
-  `<meta charset="UTF-8">` / viewport meta tags
-  The difference between named entities (`&copy;`) and numeric entities (`&#8377;`), and when only the numeric form is reliably supported

## ▶️ How to view
Open `entities_and_special_characters.html` directly in any browser — no build step or dependencies required. 🌍