# Section - 4: Project 1 - Distraction Free YouTube 🎬

This is the first hands-on project of the course — a mini clone of YouTube's homepage only using HTML, stripped down to just curated video categories with no algorithm, comments, or recommendations to get distracted by.

---

## 🎯 Project Goals
- Apply HTML learned across Sections 2 and 3 (tables, images, links, and iframes) in a real multi-page project.
- Build a homepage that links out to category-specific pages, each embedding a curated set of YouTube videos.

---

## 📁 Pages

| Page | Description |
|---|---|
| [`index.html`](./project-01/index.html) | Homepage — a table-based grid of 6 category thumbnails (Music, Coding, Web Development, Gaming, C Language, Programming), each linking to its category page |
| [`music.html`](./project-01/music.html) | Grid of embedded music videos |
| [`coding.html`](./project-01/coding.html) | Grid of embedded coding videos |
| [`web_development.html`](./project-01/web_development.html) | Grid of embedded web development videos |
| [`gaming.html`](./project-01/gaming.html) | Grid of embedded gaming videos |
| [`c_language.html`](./project-01/c_language.html) | Grid of embedded C language videos |
| [`programming.html`](./project-01/programming.html) | Grid of embedded programming videos |

---

## 🔑 Key concepts applied
- `<table>` — used for homepage grid layout (thumbnails + labels) and video grids on each category page to make the webpage look more organised since no CSS is used
- `<img>` — category thumbnails on the homepage
- `<a href="...">` — navigation between homepage and category pages, plus "Go Back" buttons on each category page
- `<iframe>` — embedding real YouTube videos, multiple per page, using `allow`, `referrerpolicy`, and `allowfullscreen`
- `<button>` wrapped in an `<a>` — the "Go Back" navigation pattern on each category page

---

## 🚧 Not yet covered here
- 🎨 Table-based layout for grids works but is a workaround — this is exactly the kind of layout CSS Grid/Flexbox (coming in Section 5-6) is built to handle properly
- 📱 No responsive behavior — fixed `width`/`height` on iframes and images won't adapt to smaller screens

---

## ▶️ How to view
Open `index.html` directly in any browser and click through the category thumbnails. Requires an internet connection — all thumbnails and videos are loaded externally. 🌍

---

## 📅 Daily Progress Log

*   **Day 06** 🎬 
    *   **Completed:** Built the full Project 1 — Distraction Free YouTube, including the homepage grid and all 6 category pages.
    *   **Achieved:** Applied tables for layout, image thumbnails linking to subpages, and multiple YouTube iframe embeds per category page in a real multi-page project instead of a single lesson file.

---

## 🏁 Conclusion

*   **Project Status:** 🎉 Fully Completed!
*   **Total Time Spent:** 1 day
*   **Final Takeaway:** First real multi-page project instead of isolated lesson files — tying together tables, links, images, and iframes to build something that actually feels like a mini site.