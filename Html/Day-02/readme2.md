# 🌐 day -2 of html

---

## 🖼️ 1. Images (`<img>`)

### ✅ Syntax

```html
<img src="image.jpg" alt="description">
```

### 🔹 Important Attributes

* `src` → Image path
* `alt` → Text if image not load
* `width` / `height` → Size

---

### 🧠 Examples

```html
<img src="images/pic.jpg" alt="local image">
<img src="../images/pic.jpg" alt="outside folder">
<img src="https://via.placeholder.com/150" alt="online image">
```

---

### ⚠️ Common Mistakes

* Wrong file path
* Missing `alt`
* Case mismatch

---

## 🔗 2. Links (`<a>`)

### ✅ Syntax

```html
<a href="URL">Link Text</a>
```

---

### 🧠 Examples

```html
<a href="https://google.com">Google</a>
<a href="day1.html">Go to Day1</a>
<a href="../index.html">Back</a>
<a href="mailto:test@gmail.com">Email</a>
<a href="tel:9876543210">Call</a>
```

---

### 🌐 Open in New Tab

```html
<a href="https://google.com" target="_blank">Open</a>
```

---

### 🖼️ Image as Link

```html
<a href="https://google.com">
  <img src="../images/pic.jpg">
</a>
```

---

## 📋 3. Lists

### 🟢 Unordered List (`<ul>`)

```html
<ul>
  <li>Apple</li>
  <li>Banana</li>
</ul>
```

---

### 🔢 Ordered List (`<ol>`)

```html
<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>
```

---

### 🔀 Nested List

```html
<ul>
  <li>Fruits
    <ul>
      <li>Apple</li>
    </ul>
  </li>
</ul>
```

---

### 🔵 Description List (`<dl>`)

```html
<dl>
  <dt>HTML</dt>
  <dd>Markup language</dd>
</dl>
```

---

## 📊 4. Tables

### ✅ Basic Structure

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>

  <tr>
    <td>Abi</td>
    <td>20</td>
  </tr>
</table>
```

---

### 🔹 Tags

* `<table>` → Table
* `<tr>` → Row
* `<th>` → Header
* `<td>` → Data

---

### 🔀 Merge Cells

#### Colspan

```html
<td colspan="2">Merged</td>
```

#### Rowspan

```html
<td rowspan="2">Merged</td>
```

---

## 📝 5. Forms

### ✅ Basic Structure

```html
<form>
  <label>Name:</label>
  <input type="text">

  <input type="submit">
</form>
```

---

### 🔹 Input Types

```html
<input type="text">
<input type="password">
<input type="email">
<input type="number">
<input type="submit">
```

---

### 🔘 Radio Button

```html
<input type="radio" name="gender"> Male
<input type="radio" name="gender"> Female
```

---

### ☑️ Checkbox

```html
<input type="checkbox"> HTML
<input type="checkbox"> CSS
```

---

### ⬇️ Dropdown

```html
<select>
  <option>India</option>
  <option>USA</option>
</select>
```

---

### 📝 Textarea

```html
<textarea></textarea>
```

---

### 🧠 Full Example

```html
<form>

  <label>Name:</label><br>
  <input type="text"><br><br>

  <label>Password:</label><br>
  <input type="password"><br><br>

  <label>Gender:</label><br>
  <input type="radio" name="g"> Male
  <input type="radio" name="g"> Female<br><br>

  <label>Skills:</label><br>
  <input type="checkbox"> HTML
  <input type="checkbox"> CSS<br><br>

  <label>Country:</label><br>
  <select>
    <option>India</option>
    <option>USA</option>
  </select><br><br>

  <input type="submit">

</form>
```

---

## 🧩 Quick Summary

* `<img>` → Show image
* `<a>` → Create link
* `<ul>`, `<ol>` → Lists
* `<table>` → Table
* `<form>` → User input

---

## 🚀 Final Tip

✔ Always check file path
✔ Use proper structure
✔ Practice small examples daily

---
