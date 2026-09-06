# 📄 13 — HTML Forms, Inputs, Labels & Buttons

## 🧭 What this lesson covers
Building a form with various input types, connecting `<label>` to inputs, and the three button types (submit, reset, button).

## 📁 File
[`forms.html`](./forms.html)

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — contains only a `<title>` (no charset or viewport meta tags yet)
-  `<body>`
-  `<h1>` — page heading: "Forms"
-  Intro paragraph on what forms are and the `<form>` tag
-  A list of common `input` types (text, password, email, number, checkbox, radio, submit, reset, button)
-  Note on the `placeholder` attribute
-  **Registration Form** — a real `<form>` with:
    - Name, Email, Phone, Password text-based inputs
    - A "Subscribe to newsletter" checkbox
    - A "Gender :" label (bold text) with Male/Female radio buttons
    - Submit, Reset, and a custom Button (with an `onclick` alert)

## 🔑 Key concepts introduced
-  `<form action="...">` — the form container and where it submits to
-  `<label for="id">` — connects descriptive text to a specific input via matching `id`
-  Input types: `text`, `email`, `tel`, `password`, `checkbox`, `radio`
-  `placeholder` — hint text shown inside an empty input
-  Radio buttons sharing the same `name` (so only one can be selected)
-  Three button behaviors: `submit` (sends the form), `reset` (clears it), `button` (custom JS action via `onclick`)

## 🚧 Not yet covered here
-  `<meta charset="UTF-8">` / viewport meta tags
-  `action="/submit_form"` isn't a real endpoint — submitting this form will 404, since there's no backend behind it yet (expected at this stage)
-  `<fieldset>` / `<legend>` — for semantically grouping related inputs like the gender radio buttons
-  Validation attributes — `required`, `minlength`, `pattern`, etc.
-  Layout via CSS instead of `<br><br>` for spacing between fields

## ▶️ How to view
Open `forms.html` directly in any browser — no build step or dependencies required. Submitting the form won't go anywhere real since there's no backend yet. 🌍