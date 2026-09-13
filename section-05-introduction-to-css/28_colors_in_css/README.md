# 📄 28 — Colors in CSS

## 🧭 What this lesson covers
Every way CSS lets you define a color — named colors, HEX, RGB, RGBA, HSL, HSLA — plus `transparent` and `currentColor`.

## 📁 Files
- [`colors.html`](./colors.html)
- [`style.css`](./style.css)

## 🏗️ Structure
-  `<!DOCTYPE html>`, `<html lang="en">`, and a properly filled `<head>` (`charset`, `viewport`, `title`, linked `style.css`)
-  `<body>`
-  **Ways to define Colors** — an ordered list walking through each color format, each with an explanation and a live CSS example: Named colors, HEX codes (+ shorthand), RGB, RGBA, HSL, HSLA
-  **Applying colors in CSS** — a combined example showing `color`, `background-color`, and `border` all using different values on one element
-  **Transparent and currentColor** — explains both keywords, with a live example showing `currentColor` inheriting from `color`
-  `style.css` mirrors every example from the HTML via matching class selectors, plus a `ul { list-style-type: disc; }` rule — replacing the deprecated `type="disc"` HTML attribute with the correct CSS equivalent

## 🔑 Key concepts introduced
-  **Named colors** — predefined keywords like `red`, `blue`, `green`
-  **HEX codes** — six-digit color values (`#00ffff`), plus 3-digit shorthand (`#fff`) when both digits in each pair match
-  **RGB** — `rgb(255, 0, 0)`, values 0-255 per channel
-  **RGBA** — RGB plus an alpha (opacity) channel, 0 (transparent) to 1 (opaque)
-  **HSL** — Hue (color angle), Saturation (intensity), Lightness (brightness)
-  **HSLA** — HSL plus alpha transparency
-  `transparent` — makes an element's color fully invisible
-  `currentColor` — reuses whatever the element's `color` property is currently set to, useful for keeping a border matched to text color automatically
-  `list-style-type` — the correct CSS property for bullet styling, replacing the deprecated HTML `type` attribute flagged repeatedly in earlier lessons

## 🚧 Not yet covered here
-  Newer color functions like `hwb()`, `lab()`, or `color-mix()`
-  Accessibility/contrast considerations when picking color combinations

## ▶️ How to view
Open `colors.html` directly in any browser — no build step or dependencies required. 🌍