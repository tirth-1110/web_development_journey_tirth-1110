# 📄 17 — Audio and Video Embedding

## 🧭 What this lesson covers
Embedding audio and video directly in a page using the `<audio>` and `<video>` tags with the `<source>` element.

## 📁 File
[`media.html`](./media.html)

## 🏗️ Structure
-  `<!DOCTYPE html>` and `<html lang="en">` — standard document declaration and language attribute
-  `<head>` — contains only a `<title>` (no charset or viewport meta tags yet)
-  `<body>`
-  `<h1>` — page heading: "Media in html."
-  **Audio** section — explanation + an `<audio controls>` element with a `<source>` pointing to `audio.mp3`
-  **Video** section — explanation + a `<video controls>` element with a `<source>` pointing to `video.mp4`

## 🔑 Key concepts introduced
-  `<audio controls>` — embeds a playable audio element with default browser playback controls
-  `<video controls>` — embeds a playable video element with default browser playback controls
-  `<source src="..." type="...">` — specifies the media file and its MIME type
-  Fallback text inside `<audio>`/`<video>` — shown only if the browser itself doesn't support the tag

## 🚧 Not yet covered here
-  `<meta charset="UTF-8">` / viewport meta tags
-  **Missing media files**: neither `audio.mp3` nor `video.mp4` actually exist in this folder — the tags reference files that aren't there, so the players will render empty/broken rather than the "unsupported browser" fallback text (that message is for tag support, not missing files)
-  Multiple `<source>` tags for format fallback (e.g. offering both `.mp4` and `.webm` for video, or `.mp3` and `.ogg` for audio) to support different browsers
-  Additional attributes like `autoplay`, `loop`, `muted`, `preload`, and `poster` (for video thumbnails)
-  Accessibility considerations — captions/subtitles via `<track>` for video

## ▶️ How to view
Open `media.html` directly in any browser — but note the audio/video players won't actually play anything until real `audio.mp3` and `video.mp4` files are added to this folder. 🌍