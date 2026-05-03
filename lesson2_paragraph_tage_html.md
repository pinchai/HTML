# Lesson 2: HTML Tags, Structure & Text Formatting

---

# Lesson Objectives

- Understand what HTML Tags are  
- Learn important Structure Tags  
- Understand Attributes  
- Write basic HTML  
- Format text properly in HTML  

---

# What is an HTML Tag?

HTML Tag = element used to build a web page

```html
<p>Content</p>
```

- Opening Tag: `<p>`
- Closing Tag: `</p>`
- Content: Text inside the tag

---

# Structure Tags

```html
<html>
<head>
<title>Page Title</title>
</head>
<body>
Content here
</body>
</html>
```

- `<html>` → root of document  
- `<head>` → metadata  
- `<body>` → visible content  
- `<title>` → tab name  

---

# Full HTML Example

```html
<!DOCTYPE html>
<html>
<head>
  <title>My Page</title>
</head>
<body>
  <h1>Hello!</h1>
  <p>This is my first HTML page.</p>
</body>
</html>
```

---

# Attributes

```html
<tag attribute="value">
```

Example:

```html
<img src="photo.jpg" alt="image">
```

---

# Common Attributes

- id  
- class  
- href  
- src  
- alt  

---

# Paragraph & Text Tags

## Paragraph

```html
<p>This is a paragraph.</p>
```

## Horizontal Rule

```html
<hr>
```

## Line Break

```html
<p>Hello<br>World</p>
```

## Preformatted

```html
<pre>
Name: John
Score: 90
</pre>
```

---

# Text Formatting

## Bold

```html
<b>Bold</b>
<strong>Important</strong>
```

## Italic

```html
<i>Italic</i>
<em>Emphasized</em>
```

## Highlight & Small

```html
<mark>Highlight</mark>
<small>Small</small>
```

## Delete & Insert

```html
<del>$50</del>
<ins>$35</ins>
```

## Sub/Sup

```html
H<sub>2</sub>O
x<sup>2</sup>
```

---

# Practice

```html
<!DOCTYPE html>
<html>
<head>
  <title>Practice</title>
</head>
<body>

<p>First paragraph</p>

<hr>

<p>Second paragraph<br>
with line break</p>

<pre>
Name: Your Name
Date: Today
</pre>

</body>
</html>
```

---

# Key Takeaways

- Tags structure HTML  
- Use semantic tags  
- Attributes add info  
- Formatting improves readability  
