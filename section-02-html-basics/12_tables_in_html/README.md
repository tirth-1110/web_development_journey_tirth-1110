# 📄 12 — Tables in HTML

## 🧭 What this lesson covers
Building structured tables with `<table>`, `<tr>`, `<th>`, `<td>`, and merging cells with `colspan`/`rowspan`.

## 📁 File
[`tables.html`](./tables.html)

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — contains only a `<title>` (no charset or viewport meta tags yet)
-  `<body>`
-  `<h1>` — page heading: "Tables"
-  Explanation of `<table>`, `<tr>`, `<td>`, `<th>`, and the `border` attribute
-  Note distinguishing table headings from table data
-  Note introducing `colspan` and `rowspan`
-  **Example Table** — a basic 3-column, 4-row table of fruits and prices
-  **Example Table with Spanning** — a second table demonstrating `rowspan` (merging Serial No. across two rows) and `colspan` (merging Fruits + Price into one cell)

## 🔑 Key concepts introduced
-  `<table>` — the table container
-  `<tr>` — table row
-  `<th>` — header cell (bold, defines column purpose)
-  `<td>` — data cell (the actual content)
-  `border` attribute — adds a visible border to the table
-  `rowspan` — merges a cell vertically across multiple rows
-  `colspan` — merges a cell horizontally across multiple columns

## 🚧 Not yet covered here
-  `<meta charset="UTF-8">` / viewport meta tags
-  `border="1"` is a deprecated HTML attribute — the modern way to style table borders is CSS (`border` property in a stylesheet)
-  Semantic table structure — `<thead>`, `<tbody>`, `<tfoot>` for separating header/body/footer sections
-  `<caption>` — for giving a table an accessible title/description
-  The rowspan example groups two *different* fruits (Chikoo, Banana) under one Serial No. — a slightly confusing choice, since rowspan is more naturally demonstrated with genuinely shared data (e.g. one category spanning multiple sub-items)

## ▶️ How to view
Open `tables.html` directly in any browser — no build step or dependencies required. 🌍