# Cyber Security End-Sem Prep · MJPRU CS-453T

Study site for **MJPRU Bareilly · B.Tech VII Semester · Cyber Security / Information Security (CS-453T, formerly CS-467N)**.

**[Open the site](https://hira04irshad.github.io/cyber-mjpru-prep/)**

## What's inside

| Page | What it gives you |
|---|---|
| **PYQ analysis** | The 2025-26 end-sem and both 2025 mid papers ranked by topic, with a predicted paper |
| **All past papers** | Every question typed out and tagged by unit, plus the syllabus |
| **How to write answers** | The MJPRU long-answer template: 4–5 pages per question, at least one diagram |
| **Video lectures** | YouTube lectures for every syllabus topic, unit by unit; tap to play on the page |
| **Unit notes 1–5** | The full syllabus, with exam definitions, diagrams, worked ciphers, RSA, DSA and the IT Act sections |
| **Mock papers 1–3** | 70-mark papers in the MJPRU pattern (any 5 of 8) with full answers; every cipher, RSA and DSA example checked |
| **Last-night sheet** | Definitions, lists, numbers and sections, diagrams to practise, worked examples |

## How it works

A static site with no build step, using the same design as [dip-mjpru-prep](https://github.com/arshanalikhan/dip-mjpru-prep): sidebar on desktop, top bar and bottom tabs on phones, light and dark themes. `index.html` holds the shell and the home page; every other page is `content/<page>.md`, loaded for the page in the URL hash and rendered with [marked](https://marked.js.org/). ` ```mermaid ` blocks are drawn with [Mermaid](https://mermaid.js.org/), `::: ans` / `::: tip` / `::: warn` blocks become styled boxes, and `@yt id | title | channel | length` lines become video cards. Progress ("mark as done") and exam mode are saved in the browser only.

```text
index.html          shell (sidebar, phone tabs) and the home page
assets/base.css     design tokens, shell and home styles
assets/cs.css       additions: Markdown pages, diagrams, answer boxes, topic bars, video cards
assets/app.js       router, Markdown + diagrams + videos, progress, exam mode, hero animation
content/*.md        every other page
```

To edit content, change the Markdown in `content/` and push to `main`; GitHub Actions publishes to GitHub Pages. When you change `assets/`, bump the `?v=` number in `index.html` so browsers fetch the new files. The end-sem date is set in `EXAM_DATE` in `assets/app.js` (currently a tentative 15 Dec 2026).

Preview locally:

```bash
python -m http.server 8794
```

## Sources

Units 1 and 2 follow the class notes and Whitman & Mattord, *Principles of Information Security*; Unit 2's X.800 material and Unit 3 follow Stallings, *Cryptography and Network Security*, and Schneier, *Applied Cryptography*; Unit 4 follows Krause & Tipton, *Handbook of Information Security Management*. The papers are from our batch (2025-26). No older MJPRU Cyber Security papers could be found online.

Not an official MJPRU resource. If anything here disagrees with your class notes, trust your teacher.
