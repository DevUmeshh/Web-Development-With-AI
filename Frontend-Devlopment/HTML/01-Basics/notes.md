# HTML — Day 1 Quick Revision

## 1. HTML

**HTML = HyperText Markup Language**

* Standard markup language for structuring web pages.
* Defines the **structure and meaning** of content.
* HTML is **not** a programming language.

---

## 2. Basic Structure

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
</head>

<body>
    <h1>Hello World</h1>
</body>

</html>
```

---

## 3. Core Elements

| Element           | Purpose                 |
| ----------------- | ----------------------- |
| `<!DOCTYPE html>` | Declares HTML5 document |
| `<html>`          | Root element            |
| `<head>`          | Metadata and resources  |
| `<body>`          | Visible page content    |
| `<title>`         | Browser tab title       |
| `<h1>` – `<h6>`   | Headings                |
| `<p>`             | Paragraph               |
| `<br>`            | Line break              |
| `<hr>`            | Thematic break          |
| `<!-- -->`        | Comment                 |

---

## 4. Element vs Tag

**Element:** Complete HTML structure.

```html
<p>Hello</p>
```

**Tag:** Markup used to create an element.

```html
<p>
</p>
```

---

## 5. Attributes

Attributes provide additional information about an element.

```html
<html lang="en">
```

```text
lang → attribute
"en" → value
```

Common attributes:

```text
id
class
href
src
alt
title
type
name
value
```

---

## 6. Headings

```html
<h1>Main Heading</h1>
<h2>Section</h2>
<h3>Subsection</h3>
```

* `h1` = highest-level heading.
* `h1`–`h6` represent heading levels.
* Use headings according to **content hierarchy**, not visual size.

---

## 7. Paragraph

```html
<p>This is a paragraph.</p>
```

Use `<p>` for a block of paragraph text.

---

## 8. Void Elements

Elements that don't require a closing tag.

Examples:

```html
<br>
<hr>
<meta>
```

---

## 9. Comments

```html
<!-- This is a comment -->
```

* Not displayed on the webpage.
* Useful for code organization and explanation.

---

## 10. Important Meta Tags

### Character Encoding

```html
<meta charset="UTF-8">
```

Defines document character encoding.

### Viewport

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Helps the page render correctly across different screen sizes.

---

## 11. Nesting

Elements can exist inside other elements.

```html
<body>
    <h1>Hello</h1>
    <p>Welcome.</p>
</body>
```

Always maintain **proper nesting**.

---

## 12. File Extension

HTML files use:

```text
.html
```

Common entry file:

```text
index.html
```

---

## 13. Basic HTML Workflow

```text
Write HTML
   ↓
Save .html
   ↓
Open in Browser
   ↓
Inspect with DevTools
   ↓
Modify & Test
```

---

## 14. Day 1 Checklist

* [x] HTML fundamentals
* [x] HTML5 document structure
* [x] `DOCTYPE`
* [x] `html`, `head`, `body`
* [x] Metadata
* [x] Headings
* [x] Paragraphs
* [x] Attributes
* [x] Comments
* [x] Nesting
* [x] Void elements
* [x] Browser testing

## One-Line Revision

> **HTML defines the structure and meaning of web content; CSS handles presentation, and JavaScript handles behavior.**
