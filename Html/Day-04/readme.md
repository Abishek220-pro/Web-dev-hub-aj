# 📦 CSS Flexbox – Complete Guide

## 🚀 Introduction

Flexbox (Flexible Box Layout) is a CSS layout module used to design flexible and responsive layouts. It helps align and distribute space among items in a container.

---

## 🧠 Basic Concept

* **Flex Container (Parent)** → Element with `display: flex`
* **Flex Items (Children)** → Elements inside the container

```css
.container {
  display: flex;
}
```

---

## 📏 Flex Direction

Defines the direction of items.

```css
.container {
  flex-direction: row;
}
```

### Values:

* `row` (default) → left to right
* `row-reverse`
* `column`
* `column-reverse`

---

## 🎯 Justify Content (Main Axis)

Controls horizontal alignment (in row mode).

```css
.container {
  justify-content: center;
}
```

### Values:

* `flex-start`
* `flex-end`
* `center`
* `space-between`
* `space-around`
* `space-evenly`

---

## 📐 Align Items (Cross Axis)

Controls vertical alignment (in row mode).

```css
.container {
  align-items: center;
}
```

### Values:

* `flex-start`
* `flex-end`
* `center`
* `stretch` (default)
* `baseline`

---

## 🔁 Flex Wrap

Allows items to move to the next line.

```css
.container {
  flex-wrap: wrap;
}
```

### Values:

* `nowrap` (default)
* `wrap`
* `wrap-reverse`

---

## ⚡ Gap (Spacing)

Adds space between items.

```css
.container {
  gap: 20px;
}
```

---

## 🧩 Flex Item Properties

### 1. flex-grow

Controls how much space an item takes.

```css
.item {
  flex-grow: 1;
}
```

---

### 2. flex-shrink

Controls shrinking behavior.

```css
.item {
  flex-shrink: 0;
}
```

---

### 3. flex-basis

Sets initial size.

```css
.item {
  flex-basis: 200px;
}
```

---

### 4. Flex Shortcut

```css
.item {
  flex: 1;
}
```

---

## 🧪 Complete Example

```html
<!DOCTYPE html>
<html>
<head>
<style>
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 20px;
  height: 300px;
  background: lightgray;
}

.box {
  width: 100px;
  height: 100px;
  background: blue;
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
</head>
<body>

<div class="container">
  <div class="box">1</div>
  <div class="box">2</div>
  <div class="box">3</div>
  <div class="box">4</div>
</div>

</body>
</html>
```

---

## 🎯 Common Use Cases

* Navigation bars
* Centering elements
* Card layouts
* Responsive designs

---

## 🔥 Pro Tips

* Use `justify-content` → Main Axis
* Use `align-items` → Cross Axis
* Use `gap` instead of margin
* Use `flex-wrap` for responsive layouts

---

## 🧠 Key Rule

> **Main Axis → justify-content**
> **Cross Axis → align-items**

---

## 🎯 Practice Tasks

1. Create a navbar using Flexbox
2. Center a div both horizontally and vertically
3. Build a responsive card layout
4. Create a grid-like layout using `flex-wrap`

---

## 📌 Next Topic

➡️ CSS Grid (Advanced Layout System)

---

## 💡 Conclusion

Flexbox is a powerful tool for building modern, responsive layouts. Mastering it will make your UI design faster, cleaner, and more efficient.

---
