# 📄 29 — Box Model in CSS

## 🧭 What this lesson covers
The four layers every HTML element is made of — Content, Padding, Border, Margin — how they stack to determine an element's actual rendered size, and the `content-box` vs `border-box` sizing models.

## 📁 Files
- [`box_model.html`](./box_model.html)
- [`style.css`](./style.css)

## 🏗️ Structure
-  `<!DOCTYPE html>`, `<html lang="en">`, and a properly filled `<head>` (`charset`, `viewport`, `title`, linked `style.css`)
-  `<body>`
-  Intro explaining every element is a rectangular box, plus an ASCII diagram of the box model layered from Content outward to Margin
-  **The Four Parts** — an ordered list covering Content, Padding, Border, and Margin, each with an explanation and a live CSS example
-  **Example** — a worked calculation showing how `width`/`height` combine with `padding` and `border` to determine actual rendered size (300px + padding + border = 350px)
-  A note on individual-side margin/padding (`margin-top`, `margin-bottom`, etc.) and shorthand syntax (`margin: 10px 20px;`)
-  **Box Sizing** section — explains `content-box` (default) vs `border-box`, with a second worked example showing `border-box` keeping total width fixed at 400px

## 🔑 Key concepts introduced
-  The box model's four layers, innermost to outermost: **Content → Padding → Border → Margin**
-  `padding` — space inside the border, pushes content inward, increases box size
-  `border` — sits between padding and margin, has width/style/color
-  `margin` — space outside the border, transparent, used for spacing between elements
-  Shorthand margin/padding syntax: `margin: 10px 20px;` (vertical, horizontal)
-  `box-sizing: content-box` (default) — `width`/`height` apply only to content
-  `box-sizing: border-box` — `width`/`height` include padding and border, keeping total size fixed

## 🚧 Not yet covered here
-  `auto` margins for centering elements
-  Negative margins
-  How `box-sizing: border-box` interacts with percentage-based widths

## ▶️ How to view
Open `box_model.html` directly in any browser — no build step or dependencies required. 🌍