# 📄 11 — Lists: Ordered and Unordered

## 🧭 What this lesson covers
All three HTML list types — ordered, unordered, and description lists — plus their type variants and nesting.

## 📁 File
[`lists.html`](./lists.html)

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — contains only a `<title>` (no charset or viewport meta tags yet)
-  `<body>`
-  `<h1>` — page heading: "Lists"
-  Intro `<ol>` naming the three list types
-  **Ordered List** section — explanation, a basic example, then three `type` variants (`1`, `A`, `a`)
-  **Unordered List** section — explanation, a basic example, then three `type` variants (`disc`, `circle`, `square`)
-  **Description List** section — explains `<dl>`, `<dt>`, `<dd>` with a fruit-themed example
-  **Nested Lists** section — an `<ol>` with `<ul>` elements nested inside, mixing bullet styles

## 🔑 Key concepts introduced
-  `<ol>` — ordered list, with `type` values `"1"`, `"A"`, `"a"` for numbering style
-  `<ul>` — unordered list, with `type` values `"disc"`, `"circle"`, `"square"` for bullet style
-  `<dl>` / `<dt>` / `<dd>` — description list, term, and description
-  Nesting one list inside another (list inside a list item)

## 🚧 Not yet covered here
-  `<meta charset="UTF-8">` / viewport meta tags
-  **Markup bug in the nested list example** — only the first `<ul>` is correctly placed inside its `<li>`; the second and third nested `<ul>` blocks sit as siblings after their `<li>` instead of inside it. Browsers auto-correct this visually, but the underlying HTML is invalid
-  `type="disc"/"circle"/"square"` on `<ul>` is a deprecated HTML attribute — the modern approach is CSS `list-style-type` instead
-  Custom list styling via CSS (`list-style-image`, `list-style-position`, etc.)

## ▶️ How to view
Open `lists.html` directly in any browser — no build step or dependencies required. 🌍