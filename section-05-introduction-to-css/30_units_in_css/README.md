# 📄 30 — Units in CSS

## 🧭 What this lesson covers
The two categories of CSS units — absolute and relative — every common unit within each, and the `calc()` function for combining them.

## 📁 Files
- [`units.html`](./units.html)
- [`style.css`](./style.css)

## 🏗️ Structure
-  `<!DOCTYPE html>`, `<html lang="en">`, and a properly filled `<head>` (`charset`, `viewport`, `title`, linked `style.css`)
-  `<body>`
-  **Two Categories of Units** — an ordered list covering Absolute Units (`px`, `pt`, `cm`, `mm`, `in`) and Relative Units (`%`, `em`, `rem`, `vw`, `vh`, `vmin`, `vmax`), each with a reference table and live CSS examples
-  **Commonly Used Units** — a deeper, practical pass over `px`, `%`, `em` vs `rem`, and `vw`/`vh`, with real-world framing for each
-  **`calc()` Function** — combining units in one value, e.g. `width: calc(100% - 200px);`
-  **Best Practices** — a short list on when to reach for `rem`, `%`/`vw`/`vh`, and when to avoid overusing `px`
-  `style.css` applies a shared `cadetblue` background to every unit example, plus table borders/padding for the two reference tables

## 🔑 Key concepts introduced
-  **Absolute units** — fixed, don't scale: `px`, `pt`, `cm`, `mm`, `in`
-  **Relative units** — scale based on parent, root, or viewport: `%`, `em` (parent's font size), `rem` (root font size), `vw`/`vh` (viewport width/height), `vmin`/`vmax` (smaller/larger viewport dimension)
-  `em` vs `rem` — `em` compounds based on nested parents, `rem` always stays relative to the root `<html>` font size, which is why `rem` is preferred for predictable typography
-  `calc()` — mixing unit types in a single value, e.g. a fixed pixel amount subtracted from a percentage

## 🚧 Not yet covered here
-  `ch` and `ex` units (character/x-height based sizing)
-  Container query units (`cqw`, `cqh`) — a newer, less universally supported addition
-  Practical responsive breakpoints combining these units with media queries

## ▶️ How to view
Open `units.html` directly in any browser — no build step or dependencies required. 🌍