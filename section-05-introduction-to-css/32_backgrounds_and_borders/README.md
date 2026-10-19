# 📄 32 — Backgrounds and Borders

## 🧭 What this lesson covers
How to style an element's background (color, image, repeat, size, position, attachment, and the shorthand) and its border (width, style, color, shorthand, per-side control, and rounded corners).

## 📁 Files
- [`backgrounds_and_borders.html`](./backgrounds_and_borders.html)
- [`style.css`](./style.css)
- [`Manga-Portal.png`](./Manga-Portal.png) (background image used by the examples)

## 🏗️ Structure
-  `<!DOCTYPE html>`, `<html lang="en">`, and a properly filled `<head>` (`charset`, `viewport`, `title`, linked `style.css`)
-  `<body>`
-  **Background Properties** — an ordered list covering `background-color`, `background-image`, `background-repeat`, `background-size`, `background-position`, `background-attachment`, and the `background` shorthand, each with a CSS example
-  **Border Properties** — an ordered list covering `border-width`, `border-style` (all eight styles, each shown separately), `border-color`, the `border` shorthand, individual side properties, and `border-radius`
-  `style.css` applies each example through a matching class selector, so every demo is visible on the `<pre>` code block that shows it

## 🔑 Key concepts introduced
-  `background-color` — solid color behind an element
-  `background-image` — image as background, referenced with `url()`
-  `background-repeat` — `repeat`, `no-repeat`, `repeat-x`, `repeat-y`
-  `background-size` — `cover`, `contain`, or explicit width and height
-  `background-position` — keywords (`center`, `top right`, etc.) or offsets (`50px 100px`)
-  `background-attachment` — `scroll` (default) or `fixed`
-  `background` shorthand — combines the above in one line, e.g. `background: url() no-repeat center/cover fixed;`
-  `border-width` — one to four values, following the same top/right/bottom/left order as margin and padding
-  `border-style` — `solid`, `dashed`, `dotted`, `double`, `groove`, `ridge`, `inset`, `outset`, `none`
-  `border-color` — one to four colors, same ordering
-  `border` shorthand — width, style, and color in one line
-  Per-side borders — `border-top`, `border-right`, `border-bottom`, `border-left`
-  `border-radius` — rounds corners; one to four values, plus percentages for circular shapes

## 🚧 Not yet covered here
-  **Factual error in the border-radius example**: the three-value comment reads "Top-left, top-right, bottom-right corners." It should say the first value sets top-left, the second sets both top-right and bottom-left, and the third sets bottom-right
-  Gradients — mentioned in the intro as a background option, but not demonstrated
-  `border-image` and `outline`
-  Background and border effects on the element itself, rather than on the code block that displays the example

## ▶️ How to view
Open `backgrounds_and_borders.html` directly in any browser — no build step or dependencies required. Keep `Manga-Portal.png` in the same folder as the HTML and CSS, since the image path is relative. 🌍