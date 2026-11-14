# Web Development Cheatsheets

A single-page, static cheatsheet for web development. It collects short code snippets with one-line explanations for HTML, CSS, JavaScript, the DOM and Git, with a sticky navigation bar to jump between sections.

## Motivation

The project was created as a learning exercise in HTML and CSS, and as a quick reference to look up commonly used syntax and Git commands while studying.

## Features

- Five cheatsheet sections: HTML, CSS, JavaScript, DOM and Git
- Each entry pairs a code snippet with a short explanation
- Sticky header with in-page navigation and smooth scrolling
- Responsive layout: code and explanation sit side by side on wide screens and stack on mobile
- Semantic HTML (`header`, `nav`, `main`, `section`, `article`, `footer`)
- No build step and no dependencies

## Tech/framework used

**Built with:**

- HTML5
- CSS3 (custom properties, flexbox, media queries)

## Code style

No linter or formatter is configured. The code uses 4-space indentation in HTML, 2-space indentation in CSS, and semantic class names such as `.cheatsheet`, `.code` and `.explanation`.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd html-css-cheatsheet
   ```
2. There are no dependencies to install and no environment to configure.
3. Open `index.html` in a browser, or serve the folder locally:
   ```bash
   python3 -m http.server 8000
   ```
   and visit <http://localhost:8000>.

## Usage examples

- Open `index.html` and use the navigation bar (HTML, CSS, JS, DOM, Git) to jump to a section.
- Scan the left column for the snippet and the right column for what it does.
- Placeholders in square brackets, such as `git add [file]`, are meant to be replaced with your own values.