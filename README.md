# Odin Recipes

A foundational web development project built as part of **The Odin Project**. The goal of this project was to practice basic HTML document structure, text formatting, lists, links, and image implementation, alongside an introduction to CSS styling.

## Live Preview

🔗 [Link](https://santhedeveloper.github.io/odin-recipes/)

## Project Overview

Odin Recipes is a simple, multi-page recipe website. It features a main index page with a navigation menu that links to individual recipe pages.

This project serves as an introduction to how the web works, focusing on linking multiple HTML files together using relative file paths and styling them with a single, shared CSS stylesheet.

## Technologies Used

- HTML5
- CSS3
- Git
- GitHub

## Features

- Multi-page architecture (Home page + 3 recipe pages)
- Correct usage of relative file paths for directory navigation
- Semantic HTML tags (headings, paragraphs, lists)
- Ordered (`<ol>`) and Unordered (`<ul>`) lists
- External CSS stylesheet linked across all pages
- Accessible image tags with `alt` attributes
- Interactive hover states on links

## What I Learned

### HTML

- **Boilerplate Structure:** How to set up a standard HTML5 document with `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>`.
- **File Paths:** Mastered the difference between absolute links (external websites) and relative links (navigating up and down local directories using `../`).
- **Semantic Elements:** Learned when to use unordered lists for ingredients and ordered lists for step-by-step instructions.
- **Accessibility:** Understood the importance of the `alt` attribute for screen readers.

### CSS

- **The Universal Reset:** Applied `box-sizing: border-box` to take control of how the browser calculates element widths.
- **Styling Text:** Modified font families, line height, text colors, and alignments.
- **Hover States:** Created interactive UI elements using the `:hover` pseudo-class.
- **Image Formatting:** Learned how to center elements using `display: block` and `margin: 0 auto`, as well as applying border radius and box shadows.

## Challenges Faced

- Understanding how relative file paths work when linking from a file inside a subdirectory (`/recipes/lasagna.html`) back to the root directory (`index.html`).
- Applying styles from a single CSS file to multiple HTML files located in different folders.

## Future Improvements

- Refactor the code to use Flexbox or CSS Grid for a more robust layout.
- Add responsive design media queries so the layout adapts perfectly to mobile screens.
- Replace the `<br />` tags with proper CSS margins for spacing.

## Credits

- Developed by **Sandeep Rout**
- Project assignment provided by **The Odin Project**
