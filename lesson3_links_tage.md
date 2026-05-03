# HTML Links (Hyperlinks)

Learn how to create and use links in HTML — one of the most fundamental building blocks of the web.

---

## 1. What is a Hyperlink?

A hyperlink is a clickable element that navigates users from one webpage to another — or to a different section of the same page.

HTML uses the `<a>` tag (anchor).

### Syntax
```html
<a href="https://example.com">
  Visit Site
</a>
```

- `<a>` → anchor tag  
- `href` → destination  
- Text → clickable content  

---

## 2. The target Attribute

Controls where the link opens.

### Same tab (default)
```html
<a href="page.html" target="_self">Same Tab</a>
```

### New tab
```html
<a href="https://google.com" target="_blank">New Tab</a>
```

### Secure new tab
```html
<a href="https://example.com"
   target="_blank"
   rel="noopener noreferrer">
  Open Safely
</a>
```

---

## 3. Absolute vs Relative URLs

### Absolute (external)
```html
<a href="https://www.google.com">Google</a>
```

### Relative (internal)
```html
<a href="about.html">About</a>
<a href="pages/contact.html">Contact</a>
```

---

## 4. Using an Image as a Link

```html
<a href="index.html">
  <img src="logo.png" alt="Home">
</a>
```

---

## 5. Email Links (mailto)

### Basic
```html
<a href="mailto:hello@example.com">Email Us</a>
```

### With subject & body
```html
<a href="mailto:hello@example.com?subject=Hello&body=Hi">
  Send Message
</a>
```

---

## 6. Phone Links (tel)

```html
<a href="tel:+15551234567">
  Call Us
</a>
```

---

## 7. Button as a Link

### Method 1
```html
<a href="signup.html">
  <button>Sign Up</button>
</a>
```

### Method 2
```html
<button onclick="location.href='signup.html'">
  Sign Up
</button>
```

### Method 3 (Best)
```html
<a href="signup.html" class="btn">
  Sign Up
</a>
```

---

## 8. Link Titles

```html
<a href="https://example.com"
   title="Opens Example"
   target="_blank">
  Visit Example
</a>
```

---

## 9. Complete Example

```html
<!DOCTYPE html>
<html>
<body>

<a href="https://www.google.com" target="_blank">Google</a>
<a href="about.html">About</a>

<a href="index.html">
  <img src="logo.png" alt="Home">
</a>

<a href="mailto:hello@example.com?subject=Hello">Email</a>
<a href="tel:+15551234567">Call</a>

<a href="signup.html"><button>Sign Up</button></a>

<a href="faq.html" title="FAQ">FAQ</a>

</body>
</html>
```
