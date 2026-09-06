# 📄 09 — Links and Anchor Tags

## 🧭 What this lesson covers
The `<a>` (anchor) tag — linking to an external site and jumping to a specific spot within the same page.

## 📁 File
[`Links.html`](./links.html)

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — contains only a `<title>` (no charset or viewport meta tags yet)
-  `<body>`
  -  `<h1>` — page heading: "Links"
  -  Intro paragraph explaining that `<a>` stands for "anchor"
  -  An external link to Google using `href` + `target="_blank"`
  -  An in-page jump link (`href="#last"`) pointing to an element with `id="last"`
  -  Several filler (Lorem Ipsum) paragraphs to create enough scroll distance to demonstrate the jump link
  -  A target paragraph (`<p id="last">`) marking where the jump link lands

## 🔑 Key concepts introduced
-  `<a href="...">` — the anchor tag, HTML's core linking element
-  External links via a full URL in `href`
-  `target="_blank"` — opens the link in a new tab
-  In-page navigation using `href="#id"` paired with a matching `id` attribute elsewhere on the page

## 🚧 Not yet covered here
-  `<meta charset="UTF-8">` / viewport meta tags
-  `rel="noopener noreferrer"` alongside `target="_blank"` — omitting it leaves a security gap (tabnabbing) and a minor performance cost; important to add whenever opening links in a new tab
-  `mailto:` / `tel:` links
-  Visual states of links (`:hover`, `:visited`, etc.) — not covered since no CSS is present yet

## ▶️ How to view
Open `links.html` directly in any browser — no build step or dependencies required. 🌍
