# Day 02 — Headings, Paragraphs, Line Breaks, and Horizontal Rules

## 📖 Purpose

Today you’ll learn how to **structure textual content** in HTML using:

- Headings (`<h1>`–`<h6>`)
- Paragraphs (`<p>`)
- Line breaks (`<br>`)
- Horizontal rules (`<hr>`)

These are the **building blocks** for readable, well-structured pages.

---

## 🗂 File: `day02.html`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Day 02 — Headings and Text Structure</title>
  </head>
  <body>
    <h1>Main Heading — Page Title</h1>
    <p>
      This is a paragraph. Paragraphs are blocks of text that are separated by
      default spacing in HTML.
    </p>

    <h2>Subheading Level 2</h2>
    <p>Subheadings help organize content into sections.</p>

    <h3>Subheading Level 3</h3>
    <p>Use lower-level headings for smaller topics.</p>

    <p>
      Sometimes you need to <br />
      break a line <br />
      without starting a new paragraph.
    </p>

    <hr />

    <p>The horizontal rule above visually separates content.</p>
  </body>
</html>
```
