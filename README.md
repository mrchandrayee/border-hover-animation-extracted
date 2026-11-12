# Border Hover Animation — extracted/reconstructed project

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/border-hover-animation-extracted/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

This project recreates the border animation shown in the uploaded screen recording.

## What is visible in the recording

The source panels show:
- HTML: a `<section>` containing an `<a href="#">Hover Me</a>` element.
- CSS reset: `margin: 0` and `padding: 0`.
- A flex-centred section with `width: 100%` and `height: 100vh`.
- An anchor styled with white text, `font-size: 30px`, `padding: 8px 15px`, and `position: relative`.
- Two pseudo-elements (`::before` and `::after`) with transparent borders and a `0.3s` transition.
- On hover, the pseudo-elements expand to full width and height and their four border edges become white.

## Run

No npm install or build step is needed.

Option 1: Open `index.html` in a browser.

Option 2: Start a local server:

```bash
python -m http.server 8000
```

Open http://localhost:8000

## Project structure

```text
border-hover-animation-extracted/
├── index.html
├── style.css
└── README.md
```

## Accuracy note

The code panels are small but the main HTML and CSS declarations are readable in the recording. The project preserves those visible declarations and fills in the surrounding page structure and responsive/accessibility details needed for a usable standalone demo. It is a reconstruction, not a claim that every line matches the creator's original CodePen.
