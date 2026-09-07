# 📄 15 — Inline vs Block Elements & HTML5 Semantic Tags

## 🧭 What this lesson covers
The difference between inline and block-level elements, then a full tour of HTML5's semantic tags applied to a real mini page layout.

## 📁 File
[`semantic_tags.html`](./semantic_tags.html)

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — contains only a `<title>` (no charset or viewport meta tags yet)
-  `<body>`
-  **Inline Elements** section — explanation + list of common inline tags (`span`, `a`, `img`, `strong`, `em`, `code`, `br`)
-  **Block Elements** section — explanation + list of common block tags (`div`, `h1`–`h6`, `p`, `ul`/`ol`, `table`, `form`)
-  **Semantic Tags** section — explanation + list of common semantic tags (`header`, `nav`, `main`, `article`, `section`, `aside`, `footer`)
-  A live example page layout built entirely from semantic tags: `header` → `nav` → `main` (with a `section`) → `aside` → `footer`

## 🔑 Key concepts introduced
-  Inline elements — don't break to a new line, only take up needed width
-  Block elements — start on a new line, take full available width
-  Semantic HTML5 tags — `header`, `nav`, `main`, `article`, `section`, `aside`, `footer` — give structural *meaning* instead of relying on generic `div`s
-  In-page navigation links using `href="#id"` (same pattern as Lecture 9, applied inside a real `nav`)
-  `&copy;` entity used correctly in the footer

## 🚧 Not yet covered here
-  `<meta charset="UTF-8">` / viewport meta tags
-  **Bug**: none of the nav links (`#home`, `#about`, `#services`, `#contact`) or aside links (`#blog`, `#portfolio`) point to an actual matching `id` anywhere on the page — same class of dangling-reference mistake as the Gender label bug in Lecture 13, just applied to anchor links instead of a label
-  `<article>` — listed in the explanation list but not actually used in the live example layout
-  Any visual layout via CSS — right now `header`, `nav`, `main`, `aside`, `footer` just stack vertically with no distinct styling

## ▶️ How to view
Open `semantic_tags.html` directly in any browser — no build step or dependencies required. The nav/aside links won't scroll anywhere yet since their target ids don't exist. 🌍