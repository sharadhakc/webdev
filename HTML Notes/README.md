# 🧱 HTML Elements & Attributes — Notes

## 🌐 What is HTML?

**HTML (HyperText Markup Language)** is the skeleton of a webpage.  
It tells the browser what each piece of content is — a heading, a paragraph, an image, etc.

A webpage is built using **elements**, and elements often have **attributes** that give extra info or behavior.

---

## 🧩 Example of Common HTML Elements

| Element | Purpose | Example |
|----------|----------|----------|
| `<h1>` – `<h6>` | Headings (largest to smallest) | `<h1>Title</h1>` |
| `<p>` | Paragraph of text | `<p>Hello world!</p>` |
| `<a>` | Link | `<a href="https://example.com">Visit</a>` |
| `<img>` | Image | `<img src="cat.jpg" alt="A cute cat">` |
| `<div>` | Block container for grouping content | `<div>...</div>` |
| `<span>` | Inline container for small text styling | `<span>highlight</span>` |
| `<ul>` / `<ol>` | Unordered / ordered list | `<ul><li>Item</li></ul>` |
| `<li>` | List item | `<li>Apple</li>` |
| `<table>` | Table container | `<table>...</table>` |
| `<tr>` | Table row | `<tr>...</tr>` |
| `<td>` | Table cell | `<td>Data</td>` |
| `<form>` | User input form | `<form>...</form>` |
| `<input>` | Input field | `<input type="text">` |
| `<button>` | Button | `<button>Click</button>` |
| `<link>` | Links external files (like CSS) | `<link rel="stylesheet" href="style.css">` |
| `<meta>` | Metadata about the page | `<meta charset="UTF-8">` |
| `<title>` | Page title (shown on tab) | `<title>My Site</title>` |
| `<header>`, `<footer>`, `<main>`, `<section>`, `<article>` | Semantic layout tags | `<header>Site Title</header>` |

---

## ⚙️ Types of Attributes

### 🌍 Global Attributes
These can be used on **almost any element**.

| Attribute | Description | Example |
|------------|--------------|----------|
| `id` | Unique name for one element | `<p id="intro">...</p>` |
| `class` | Groups multiple elements for CSS | `<div class="card">...</div>` |
| `style` | Adds inline CSS directly | `<h1 style="color: red;">Hi</h1>` |
| `title` | Tooltip text on hover | `<img title="Cute cat">` |
| `hidden` | Hides the element | `<p hidden>Secret</p>` |
| `lang` | Sets language | `<html lang="en">` |
| `dir` | Text direction (ltr/rtl) | `<p dir="rtl">مرحبا</p>` |
| `tabindex` | Keyboard tab order | `<button tabindex="1">Click</button>` |

---

### 🧩 Element-Specific Attributes
These only work for certain tags.

| Element | Attribute | Description | Example |
|----------|------------|--------------|----------|
| `<a>` | `href` | URL of the link | `<a href="page.html">Link</a>` |
| `<a>` | `target` | Where to open link (`_blank`, `_self`) | `<a href="..." target="_blank">` |
| `<img>` | `src` | Image path | `<img src="photo.jpg">` |
| `<img>` | `alt` | Text if image can’t load | `<img alt="A flower">` |
| `<input>` | `type` | Input type (text, password, etc.) | `<input type="text">` |
| `<input>` | `value` | Default value | `<input value="Hello">` |
| `<form>` | `action` | URL where form submits | `<form action="/submit">` |
| `<video>` | `controls` | Adds play/pause buttons | `<video controls>` |
| `<label>` | `for` | Connects to an input’s ID | `<label for="name">Name</label>` |

---

💡 **Notes**
- `style`, `id`, `class`, and `title` can be used on most elements.  
- `href`, `src`, `alt`, etc. are *element-specific*.  
- Keep your HTML semantic (use tags for their real purpose).  
- Prefer CSS files for styling instead of inline `style` attributes.

---

✅ **Best Practice:**
Use `id` for one-time elements, and `class` for reusable styling groups.
