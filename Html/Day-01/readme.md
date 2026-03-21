# 🌐 HTML Day 1 Notes

---

## 📌 What is HTML?

HTML (**HyperText Markup Language**) is the standard language used to create and structure content on the web.

* It is **not a programming language**
* It uses **tags** to tell the browser how to display content
* Used to create:

  * Text
  * Images
  * Links
  * Web pages

---

## 🧱 Basic Structure of HTML

### 1. `<!DOCTYPE html>`

* Declares the document type as **HTML5**
* Helps the browser render the page correctly

---

### 2. `<html> ... </html>`

* Root element of the HTML document
* All content must be inside this tag

---

### 3. `<head> ... </head>`

* Contains **metadata** (not visible on webpage)

#### Used for:

* Page title
* Linking CSS
* Meta/SEO information

---

### 4. `<body> ... </body>`

* Contains **all visible content**

#### Includes:

* Headings
* Paragraphs
* Images
* Links

---

## 🧩 Semantic Tags (Important)

👉 These tags give **meaning (structure)** to your webpage

---

### 🔝 `<header>`

👉 Top part of the page

* Logo
* Website name

---

### 🔗 `<nav>`

👉 Navigation menu
Example:

```
Home | About | Contact
```

---

### 🧠 `<main>`

👉 Main content area

* Everything between header and footer
* Contains important content

---

### 📦 `<section>`

👉 Small block inside main

* Used to group related content

---

### 📰 `<article>`

👉 Independent content

* Blog post
* News article
* Can stand alone

---

### 🔚 `<footer>`

👉 Bottom part of page

* Copyright
* Contact info

---

## 🔄 Simple Page Flow

```
<header>
   Logo / Title
</header>

<nav>
   Menu
</nav>

<main>
   <section>
      <article>
         Content
      </article>
   </section>
</main>

<footer>
   Bottom info
</footer>
```

---

## 🧠 Quick Summary

* HTML = Structure of webpage
* Uses tags like `<html>`, `<head>`, `<body>`
* Semantic tags improve structure and readability

---
