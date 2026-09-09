# 📄 20 — Internal vs External Links

## 🧭 What this lesson covers
The difference between **internal links** (pointing to pages/sections within the same site) and **external links** (pointing to a different domain), and the `<a>` tag attributes that go along with each.

## 📁 File
[`internal_and_external_links.html`](./internal_and_external_links.html)

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — `charset`, `viewport`, and `title`
-  `<body>`
-  **Internal Links** section — explanation + examples linking to another page in the site and to an in-page anchor (`#id`)
-  **External Links** section — explanation + examples linking out to other websites, with `target="_blank"` and `rel="noopener noreferrer"`

## 🔑 Key concepts introduced
-  `<a href="about.html">` — internal link using a relative path
-  `<a href="#section2">` — internal link jumping to an anchor on the same page
-  `<a href="https://example.com">` — external link using an absolute URL
-  `target="_blank"` — opens the external link in a new tab
-  `rel="noopener noreferrer"` — added alongside `target="_blank"` to prevent the new tab from accessing `window.opener` (security) and to avoid leaking referrer info
-  Relative vs absolute paths as the main structural difference between the two link types

## 🚧 Not yet covered here
-  `rel="nofollow"` / `rel="sponsored"` and how they affect SEO link equity
-  Styling visited vs unvisited links (`:link`, `:visited` pseudo-classes)
-  Linking to non-HTML resources (PDFs, emails via `mailto:`, phone numbers via `tel:`)

## ▶️ How to view
Open `links.html` directly in any browser — no build step or dependencies required. Click through the internal links to confirm same-page/site navigation, and the external links to confirm they open in a new tab. 🌍