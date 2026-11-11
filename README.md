# Analog Circuits CT-01 Study Hub

A static educational website built in the style and navigation pattern of the reference ECE study hub, rewritten with original Analog Circuit CT-01 content from the user's uploaded course notes and textbook.

## Open locally

1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge, Safari, or Firefox.
3. The site works without a server; only optional Google web fonts require internet.

## Deploy with GitHub Pages

1. Create a public GitHub repository such as `analog-circuit-ct`.
2. Upload **all files and folders**, preserving `assets/` and `resources/`.
3. Open **Settings → Pages → Build and deployment**.
4. Set **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
5. GitHub Pages will publish the website at your repository Pages URL.

Do not upload only the HTML file: the CSS, JavaScript, and PDFs are separate assets.

## Contents

- Preparation: handwritten lecture-based syllabus, diode models, load-line, series and parallel diode problems, diode AND / OR gates, rectifiers, clippers, clampers and Zener calculations.
- Solutions: 20-mark mock test, pauseable timer, complete answers, expandable exercises, persistent revision checklist.
- Resources: the original course PDFs (handwritten note PDF has been optimized for web), and generated study and formula guides.
- Interactive calculators: diode series calculator, Zener shunt-regulator calculator.
- Interactive visualization: waveforms for rectifiers, clippers, and clampers.
- Features: light / dark theme, responsive sidebar, contents navigation, print action, reading progress.

## Source and accuracy notes

The user provided a 22-page handwritten notebook and a 74-page textbook Chapter 2 PDF. These determine the curriculum. The reference website concerns a different class (three-phase Circuits & Systems II) and its course content has *not* been copied. Chapter 2 section 2.10 covers Zener diodes; section 2.11 covers voltage multipliers and is omitted.

Some SVGs are conceptual / illustrative and do not replace careful examination of circuit polarity in the class notes. The simple calculators assume approximate diode models and do not verify device thermal ratings.

No backend is required. No data is transmitted. Local progress data is kept in the browser's localStorage when available.
