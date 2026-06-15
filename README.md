# 🧾 HTML Practice Projects

A collection of beginner-friendly HTML-only projects to practice markup, structure, and layout design. No CSS or JavaScript—just clean, semantic HTML.

## 📁 Projects Included

### `01-personal-portfolio/`
A simple portfolio page with sections for introduction, projects, and contact.

🔗 Challenge: [roadmap.sh/projects/portfolio-website](https://roadmap.sh/projects/portfolio-website)

### `02-single-page-cv/`
A resume-style single HTML page that includes personal info, education, and experience.

🔗 Challenge: [roadmap.sh/projects/single-page-cv](https://roadmap.sh/projects/single-page-cv)

### `03-basic-website/`
A multi-page basic site with:
- `index.html`: Home page
- `about.html`: About section
- `contact.html`: Contact details

🔗 Challenge: [roadmap.sh/projects/basic-html-website](https://roadmap.sh/projects/basic-html-website)

### `04-pricing-comparison-table/`
An accessible pricing page comparing three subscription plans in a real `<table>` with a `<caption>`, `<thead>`/`<tbody>`, `scope="col"`/`scope="row"` headers, and a merged (`colspan`) highlight row.

🔗 Challenge: [roadmap.sh/projects/pricing-comparison-table](https://roadmap.sh/projects/pricing-comparison-table)

### `05-blog-post-page/`
A single semantic blog post page using `<header>`/`<main>`/`<article>`/`<footer>`, a proper heading outline (`<h1>`→`<h2>`→`<h3>`), real text elements (lists, `<blockquote>`+`<cite>`, `<pre>`/`<code>`, `<em>`/`<strong>`), a `<figure>` with `<figcaption>`, descriptive links, and full head metadata including a meta description.

🔗 Challenge: [roadmap.sh/projects/blog-post-page](https://roadmap.sh/projects/blog-post-page)

### `06-contact-form/`
An accessible, JavaScript-free contact form with `action`/`method="post"`, labelled inputs (text, email, `<select>`, `<textarea>`), browser validation (`required`, `minlength`, `type="email"`), radio buttons grouped in a `<fieldset>`+`<legend>`, an optional newsletter checkbox, and a submit button.

🔗 Challenge: [roadmap.sh/projects/contact-form](https://roadmap.sh/projects/contact-form)

### `07-photo-showcase/`
An image gallery page demonstrating media markup: six `<img>` elements with descriptive `alt` and `width`/`height`, three wrapped in `<figure>`+`<figcaption>`, one decorative image with `alt=""`, and an embedded `<video>` with `controls`, a `poster`, and fallback text.

🔗 Challenge: [roadmap.sh/projects/photo-showcase](https://roadmap.sh/projects/photo-showcase)

## 💡 Purpose

These projects are designed to help you:

- Practice clean HTML structure
- Use semantic tags (`<section>`, `<article>`, `<header>`, etc.)
- Build without dependencies or frameworks
- Understand basic page navigation

## 🧠 How to Use

Open any `index.html` file in a browser. No server setup needed.

## 📦 File Structure

```bash
html-practice-projects/
├── 01-personal-portfolio/
│   └── index.html
├── 02-single-page-cv/
│   └── index.html
├── 03-basic-website/
│   ├── index.html
│   ├── about.html
│   └── contact.html
├── 04-pricing-comparison-table/
│   └── pricing-table.html
├── 05-blog-post-page/
│   └── blog.html
├── 06-contact-form/
│   └── form.html
├── 07-photo-showcase/
│   └── showcase.html
├── .gitignore
└── README.md
