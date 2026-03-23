# 🎨 CSS Background & Box Sizing Notes

## 📌 1. Background in CSS

Background is used to style the area behind content (like body, div, section).

---

## 🎯 Background Properties

### ✅ 1. `background-color`

Sets a solid color.

```css
body {
    background-color: lightblue;
}
```

---

### ✅ 2. `background-image`

Adds an image as background.

```css
body {
    background-image: url("image.jpg");
}
```

---

### ✅ 3. `background-repeat`

Controls repeating of image.

```css
background-repeat: no-repeat;
```

**Values:**

* repeat (default)
* no-repeat
* repeat-x
* repeat-y

---

### ✅ 4. `background-size`

Controls image size.

```css
background-size: cover;
```

**Values:**

* cover → fills full screen
* contain → fits inside

---

### ✅ 5. `background-position`

Sets image position.

```css
background-position: center;
```

---

### ✅ 6. `background-attachment`

Controls scroll behavior.

```css
background-attachment: fixed;
```

* fixed → stays in place
* scroll → moves with page

---

## 🧩 Full Example

```css
body {
    background-color: lightgray;
    background-image: url("bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}
```

---

# 📦 2. Box Sizing (Width & Height)

Used to control the size of elements.

---

## 🎯 Making a Square Box

```css
.box {
    width: 300px;
    height: 300px;
}
```

👉 Equal width and height = Square

---

## 🎯 Centering the Box

```css
.box {
    margin: 50px auto;
}
```

---

## 🎯 Adding Space Inside

```css
.box {
    padding: 20px;
}
```

---

## 🎯 Full Box Example

```css
.box {
    width: 300px;
    height: 300px;
    background-color: #1ca3d1;
    border: 2px solid black;
    margin: 50px auto;
    padding: 20px;
    text-align: center;
}
```

---

## ⚠️ Common Mistakes

* Wrong image path ❌
* Missing `width` or `height` ❌
* Using large images (slow loading) ❌
* Content overflowing box ❌

---

## 🚀 Quick Summary

* `background-color` → color
* `background-image` → image
* `size` → fit image
* `position` → place image
* `repeat` → repeat image
* `width = height` → square box

---

## 💡 Pro Tip

Use `min-height` instead of fixed height if content may grow:

```css
min-height: 300px;
```

------