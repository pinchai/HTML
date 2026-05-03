# HTML Lists

## 1. Unordered HTML List

Used when order does NOT matter (bullet points).

### Syntax

```html
<ul>
  <li>Apple</li>
  <li>Banana</li>
  <li>Orange</li>
</ul>
```

### Bullet Types (CSS)

```html
<ul style="list-style-type: square;">
  <li>Item 1</li>
</ul>
```

Types:

- disc (default)
- circle
- square
- none

---

## 2. Ordered HTML List

Used when order DOES matter (steps or sequence).

### Syntax

```html
<ol>
  <li>Wake up</li>
  <li>Eat breakfast</li>
  <li>Go to work</li>
</ol>
```

### List Types

```html
<ol type="A">
  <li>Item</li>
</ol>
```

Options:

- 1 → 1, 2, 3
- A → A, B, C
- a → a, b, c
- I → I, II, III
- i → i, ii, iii

---

## 3. Description List

Used for terms and descriptions.

### Syntax

```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>

  <dt>CSS</dt>
  <dd>Style sheet language</dd>
</dl>
```

---

## 4. HTML List Tags Summary

| Tag  | Description      |
| ---- | ---------------- |
| <ul> | Unordered list   |
| <ol> | Ordered list     |
| <li> | List item        |
| <dl> | Description list |
| <dt> | Term             |
| <dd> | Description      |

---

## 5. Nested List Example

```html
<ul>
  <li>
    Fruits
    <ul>
      <li>Apple</li>
      <li>Banana</li>
    </ul>
  </li>
  <li>Vegetables</li>
</ul>
```

---

# Quiz: HTML Lists

## Multiple Choice Questions

1. Which tag is used to create an unordered list?
   - A. `<ol>`
   - B. `<ul>`
   - C. `<li>`
   - D. `<dl>`

2. Which tag represents a list item?
   - A. `<item>`
   - B. `<list>`
   - C. `<li>`
   - D. `<dt>`

3. Which attribute changes the numbering style in an ordered list?
   - A. style
   - B. type
   - C. class
   - D. id

4. Which tag is used for description lists?
   - A. `<ul>`
   - B. `<ol>`
   - C. `<dl>`
   - D. `<dd>`

5. What does `<dt>` represent?
   - A. Data text
   - B. Description text
   - C. Definition term
   - D. Document type

---

## Answer Key

1. B
2. C
3. B
4. C
5. C

---

# Exercises

## Exercise 1: Basic Unordered List

Create an unordered list of your 5 favorite foods.

---

## Exercise 2: Ordered List

Create an ordered list showing steps to cook instant noodles.

---

## Exercise 3: Description List

Create a description list for the following:

- HTML
- CSS
- JavaScript

---

## Exercise 4: Nested List

Create a nested list like this:

- Programming
  - Python
  - JavaScript
- Database
  - MySQL
  - MongoDB

---

## Exercise 5: Custom List Style

Create an unordered list and change the bullet style to square.

---
