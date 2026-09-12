# 📄 27 — CSS Syntax and Selectors

## 🧭 What this lesson covers
The basic anatomy of a CSS rule (selector, declaration block, property, value), followed by a full tour of CSS selector types.

## 📁 Files
- [`css_selectors.html`](./css_selectors.html)
- [`style.css`](./style.css)

## 🏗️ Structure
-  `<!DOCTYPE html>`, `<html lang="en">`, and a properly filled `<head>` (`charset`, `viewport`, `title`, and linked `style.css`)
-  `<body>`
-  **CSS Syntax** section — explains selector/declaration block/property/value using a worked `h1` example
-  **Types of Selectors** section — an ordered list covering, in order: Element, Class, ID, Universal, Grouping, Descendant, and Combination (class + element) selectors, each with an explanation and a live HTML/CSS example
-  `style.css` applies several of these exact selector types to the page itself — element (`h2`), class (`.css_syntax`, `.selectors`), ID (`#ul`, `#example`), grouping (`pre, .css, .html`), descendant (`ol p`), and combination (`p.note`)

## 🔑 Key concepts introduced
-  Selector → declaration block → property → value — the anatomy of a CSS rule
-  **Element selector** — targets all elements of a tag type (`p { }`)
-  **Class selector** — targets elements sharing a class (`.highlight { }`)
-  **ID selector** — targets one unique element (`#paragraph { }`)
-  **Universal selector** — targets everything on the page (`* { }`)
-  **Grouping selector** — applies one rule to multiple selectors at once (`h1, h2, h3 { }`)
-  **Descendant selector** — targets elements nested inside another (`div p { }`)
-  **Combination selector** — narrows an element selector by class (`p.note { }`)

## 🚧 Not yet covered here
-  Pseudo-classes (`:hover`, `:first-child`, etc.) and pseudo-elements (`::before`, `::after`)
-  Attribute selectors (`[type="text"]`)
-  Specificity comparison between multiple selector types applied to the same element

## ▶️ How to view
Open `css_selectors.html` directly in any browser — no build step or dependencies required. 🌍