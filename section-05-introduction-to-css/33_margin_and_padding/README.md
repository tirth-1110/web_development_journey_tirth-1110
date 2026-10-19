# 📄 33 — Margin and Padding

## 🧭 What this lesson covers
The difference between padding (space inside an element's border) and margin (space outside it), with each property's all-sides, individual-side, and shorthand forms, plus horizontal centering with `auto` margins and margin collapse.

## 📁 Files
- [`margin_and_padding.html`](./margin_and_padding.html)
- [`style.css`](./style.css)

## 🏗️ Structure
-  `<!DOCTYPE html>`, `<html lang="en">`, and a properly filled `<head>` (`charset`, `viewport`, `title`, linked `style.css`)
-  `<body>`
-  Intro paragraph introducing margin and padding as part of the box model
-  **Padding vs Margin** — a comparison table covering where each applies and what it affects
-  **Padding** — all-sides, individual-side, and shorthand examples
-  **Margin** — all-sides, individual-side, and shorthand examples
-  **Auto Margin (Horizontal Centering)** — `margin: 0 auto;` centering a fixed-width element
-  **Margin collapse** — two vertical margins meeting, where the larger one wins instead of their sum
-  `style.css` provides a matching class for each example

## 🔑 Key concepts introduced
-  `padding` — space between an element's content and its border; increases the element's visible size
-  `margin` — space between an element's border and neighboring elements; does not change the element's own size
-  Individual sides — `padding-top`, `padding-right`, `padding-bottom`, `padding-left` (and the same for `margin`)
-  Shorthand, four values — `top right bottom left`, clockwise from the top
-  Shorthand, two values — `top-bottom | right-left`
-  Shorthand, one value — applies to all four sides
-  `margin: auto` — when set on left and right, the browser splits the free space equally, centering a block element with a set width
-  Margin collapse — adjacent vertical margins combine into the larger value, not their sum

## 🚧 Not yet covered here
-  Percentage-based margins and padding
-  Negative margins
-  Vertical margins on inline elements, which do not apply

## ▶️ How to view
Open `margin_and_padding.html` directly in any browser — no build step or dependencies required. 🌍