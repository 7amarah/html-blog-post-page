# HTML Blog Post Page

A simple, semantic, accessible blog post page built using plain HTML5.

This project was developed as part of the HTML Fundamentals learning path on [roadmap.sh](https://roadmap.sh/projects/blog-post-page), with a focus on marking up long-form content with semantic regions, the right text elements, and descriptive links.

## Live Demo

[View the Live Blog Post Page](https://7amarah.github.io/html-blog-post-page/)

## Project Overview

The objective of this project is to build a single blog post page using only HTML, without CSS or JavaScript. The page is intentionally unstyled; styling is addressed in a later project. The focus is on the structure that a reader, a screen reader, and a search engine will all see.

The page contains one post, *Why Semantic HTML Matters*, which is itself about the topic the project teaches.

## Features

- Page regions: `<header>` (site name and primary navigation), `<main>` containing a single `<article>`, and `<footer>` (copyright).
- A single `<h1>` for the post title, with `<h2>` and `<h3>` used for real subsections and no skipped heading levels.
- Paragraphs in `<p>`, an unordered list (`<ul>`) and an ordered list (`<ol>`).
- A `<blockquote>` with a `cite` attribute and a `<cite>` element naming the source.
- Inline `<code>` and a `<pre><code>` block for a code sample.
- Emphasis with meaning: `<em>` for stress and `<strong>` for importance.
- The publication date marked up with `<time datetime="2026-05-20">`.
- Descriptive link text on every link, with no "click here" or "read more".
- One `<img>` with a useful `alt`, wrapped in a `<figure>` with a `<figcaption>`.
- Head metadata: `<title>`, `<meta charset>`, `<meta viewport>`, a meta description, SEO and Open Graph metadata.

## Page Structure

| Region / Element | Purpose                                              |
| ---------------- | ---------------------------------------------------- |
| `<header>`       | Site name and primary navigation (`<nav>` with a list) |
| `<main>`         | The dominant content of the page                     |
| `<article>`      | The self-contained blog post                         |
| `<h1>`           | Post title (only one on the page)                    |
| `<h2>`           | Main sections: What Semantic HTML Means, Benefits, Examples, Learn More |
| `<h3>`           | Subsections: Accessibility, Search Engine Optimization, Maintainability, Page Regions, Code Sample |
| `<figure>`       | Image with `alt` text and `<figcaption>`             |
| `<footer>`       | Copyright notice                                     |

*Note: The "About" and "Contact" navigation links use `#` as a placeholder because this project has only one page.*

## Technologies Used

- HTML5
- Semantic HTML
- SEO metadata
- Open Graph metadata

## Project Structure

```text
html-blog-post-page/
├── index.html
├── README.md
├── mountains-at-sunrise-view.jpg
├── favicon.ico
├── favicon-16x16.png
├── favicon-32x32.png
├── apple-touch-icon.png
├── site.webmanifest
└── og-image.png
```

*Note: Some assets are optional and should only be included if they are present in the repository and referenced by the HTML document.*

## Getting Started

### Prerequisites

You only need:

- A web browser.
- A code editor (such as Visual Studio Code).
- Git (optional, for cloning the repository).

### Running Locally

1. Clone the repository:

   ```bash
   git clone git@github.com:7amarah/html-blog-post-page.git
   ```

2. Navigate into the project directory:

   ```bash
   cd html-blog-post-page
   ```

3. Open `index.html` directly in your browser.

Alternatively, open the project in Visual Studio Code and use the Live Server extension to preview the webpage.

No package installation, build process, or development server is required.

## Deployment

The project is hosted using GitHub Pages.

To deploy:

1. Push the project files to the `main` branch of the public GitHub repository.
2. Navigate to the repository's **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose `main` and `/ (root)` as the deployment source.
5. Save the configuration.

GitHub Pages will publish the webpage.

## Learning Objectives

This project demonstrates an understanding of:

- Structuring a page with `<header>`, `<main>`, `<article>` and `<footer>`.
- Using one `<h1>` and a logical `<h2>`/`<h3>` hierarchy without skipping levels.
- Choosing the right text elements: lists, quotes, `<code>` and `<pre>`.
- Using `<em>` and `<strong>` for meaning rather than appearance.
- Writing descriptive link text.
- Using `<figure>`, `<figcaption>` and meaningful `alt` text, and why a caption is not a replacement for `alt`.
- Basic search engine optimisation and Open Graph metadata.
- Static website hosting using GitHub Pages.

## Author

**Tamarabrakaemi Waritimi**

- GitHub: [@7amarah](https://github.com/7amarah)
- LinkedIn: [Tamarah Waritimi](https://www.linkedin.com/in/tamarah-waritimi-4850bb111)