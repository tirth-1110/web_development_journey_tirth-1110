# 📄 26 — Introduction to CSS

## 🧭 What this lesson covers
What CSS is and why it exists, the three ways to apply it to HTML (inline, internal, external), and the basic anatomy of a CSS rule.

## 📁 File
[`css_basics.html`](./css_basics.html)

## 🏗️ Structure
-  `<!DOCTYPE html>`, `<html lang="en">`, and a properly filled `<head>` (`charset`, `viewport`, `title`)
-  `<body>`
-  `<h1>` — "CSS", with an intro paragraph on what it is and why it exists
-  **Why CSS?** — a list of what CSS enables (colors/fonts, spacing/layout, responsive design, animations, separation of concerns)
-  **How CSS works with HTML** — the three application methods, each with a live rendered example: Inline (`style` attribute), Internal (`<style>` in `<head>`), External (`<link rel="stylesheet">`)
-  **The "Cascading" in CSS** — explains specificity, order of appearance, and `!important` as tie-breakers
-  **Anatomy of a CSS rule** — breaks down selector, property, and value with a worked example

## 🔑 Key concepts introduced
-  CSS = Cascading Style Sheets — separates visual styling from HTML structure
-  Inline CSS — `style="..."` directly on an element
-  Internal CSS — `<style>` block inside `<head>`
-  External CSS — a separate `.css` file linked via `<link rel="stylesheet" href="...">`, the recommended real-world approach
-  The "cascade" — how conflicting rules are resolved (specificity, order, `!important`)
-  Selector → property → value — the basic building block of every CSS rule

## 🚧 Not yet covered here
-  CSS selectors beyond the element selector (classes, ids, combinators) — only `p { }` is shown here
-  Specificity actually being calculated/compared with a concrete conflicting-rules example

## ▶️ How to view
Open `css_basics.html` directly in any browser — no build step or dependencies required. 🌍