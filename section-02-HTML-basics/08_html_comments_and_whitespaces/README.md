# 📄 08 — HTML Comments and Whitespaces

## 🧭 What this lesson covers
Two separate concepts bundled into one folder: how to write HTML comments, and how HTML collapses whitespace unless told otherwise.

## 📁 Files
- `comments.html`
- `whitespaces.html`

## 🏗️ Structure

### 💬 `comments.html`
-  `<!DOCTYPE html>` and `<html lang="en">`
-  `<head>` — `<title>` only
-  `<body>`
  -  Intro paragraph explaining what comments are
  -  A single-line comment (`<!-- ... -->`), demonstrated inside an otherwise-empty `<p>`
  -  A multi-line comment, same pattern
  -  A paragraph noting the `Ctrl + /` editor shortcut and manual comment syntax
  -  A closing note: comments are invisible in the rendered page but visible via "View Source" / DevTools — so never put sensitive info in them

### ⬜ `whitespaces.html`
-  `<!DOCTYPE html>` and `<html lang="en">`
-  `<head>` — `<title>` only
-  `<body>`
  -  A paragraph with many extra spaces typed in, showing the browser collapses them to one
  -  A note introducing `<pre>`
  -  A `<pre>` block (wrapping a `<p>`) demonstrating that spacing and line breaks are preserved inside it

## 🔑 Key concepts introduced
-  HTML comment syntax: `<!-- comment -->`
-  HTML whitespace collapsing behavior (multiple spaces → one space)
-  `<pre>` — preserves whitespace and line breaks exactly as typed
-  Comments are stripped from render but still visible in page source

## 🚧 Not yet covered here
-  `<meta charset="UTF-8">` / viewport meta tags
-  That commenting out a paragraph (`<p><!-- text --></p>`) leaves an empty, valid-but-pointless paragraph tag — comments are usually placed *between* elements, not wrapping content inside one
-  That `<pre>` renders in a monospace font by default — not demonstrated visually here
-  Nesting `<p>` inside `<pre>` is unusual in practice; typically `<pre>` wraps plain text or `<code>`, not block-level elements

## ▶️ How to view
Open `comments.html` and `whitespaces.html` directly in any browser — no build step or dependencies required. To actually see the comments, right-click → "View Page Source" or open DevTools. 🌍
