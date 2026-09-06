# 📄 07 — Formatting Text (Bold, Italics, Underline & More)

## 🧭 What this lesson covers
Inline text-formatting tags — bold, italic, underline, strikethrough, subscript, superscript — and how they can be nested/combined.

## 📁 File
`bold_italics_underline.html`

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — contains only a `<title>` (no charset or viewport meta tags yet)
-  `<body>` — eight `<p>` elements, each demonstrating one formatting tag (or a combination) inline within a sentence

## 🔑 Key concepts introduced
-  `<b>` — bold text (visual weight only)
-  `<i>` — italic text (visual style only)
-  `<u>` — underlined text
-  `<s>` — strikethrough (marks text as no longer accurate/relevant)
-  `<del>` — strikethrough (marks text as deleted/removed)
-  `<sub>` — subscript
-  `<sup>` — superscript
-  Nesting multiple formatting tags together (e.g. `<b><i><u>...</u></i></b>`)

## 🚧 Not yet covered here
-  `<meta charset="UTF-8">` / viewport meta tags
-  Semantic equivalents — `<strong>` (importance) vs `<b>` (style only), `<em>` (emphasis) vs `<i>` (style only)
-  When to use `<s>` vs `<del>` (accuracy vs. removal/tracked changes) — this file treats them as the same thing
-  Accessibility note: `<u>` can visually be confused with links, so it's used sparingly in real projects

## ▶️ How to view
Open `bold_italics_underline.html` directly in any browser — no build step or dependencies required. 🌍
