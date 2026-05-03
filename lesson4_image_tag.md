# HTML Images

## 1. HTML Image Syntax
Use the `<img>` tag (self-closing):

```html
<img src="image.jpg" alt="Description">
```

- `<img>` = image tag  
- `src` = image path  
- `alt` = alternative text  

---

## 2. The `src` Attribute
Defines the **path to the image**.

```html
<img src="cat.jpg" alt="Cat">
```

### Types of paths:
- Same folder → `"cat.jpg"`
- Subfolder → `"images/cat.jpg"`
- Full URL → `"https://example.com/cat.jpg"`

---

## 3. The `alt` Attribute
Provides **alternative text** if the image cannot load.

```html
<img src="cat.jpg" alt="Cute cat sleeping">
```

Important for:
- Accessibility (screen readers)  
- SEO  
- Broken images  

---

## 4. Image Size – Width & Height

```html
<img src="cat.jpg" width="300" height="200">
```

Using CSS:

```html
<img src="cat.jpg" style="width:300px; height:200px;">
```

---

## 5. Width & Height vs Style

| Method | Use Case |
|--------|---------|
| HTML attributes | Quick/simple |
| CSS (style) | Recommended, flexible |

Best practice:

```html
<img src="cat.jpg" style="width:100%; height:auto;">
```

---

## 6. Images in Another Folder

```html
<img src="images/cat.jpg" alt="Cat">
```

---

## 7. Images on Another Website

```html
<img src="https://www.example.com/cat.jpg" alt="Cat">
```

---

## 8. Animated Images (GIF)

```html
<img src="animation.gif" alt="Animated image">
```

---

## 9. Image as a Link

```html
<a href="https://example.com">
    <img src="cat.jpg" alt="Cat">
</a>
```

---

## 10. Image Floating

```html
<img src="cat.jpg" style="float:right; margin:10px;">
<p>This text wraps around the image.</p>
```

---

## 11. Common Image Formats

| Format | Description |
|--------|------------|
| JPG / JPEG | Good for photos |
| PNG | Transparent background |
| GIF | Animation |
| SVG | Vector (scalable) |
| WebP | Modern, smaller size |

---

## Summary
- Use `<img>` tag  
- `src` = image path  
- `alt` = accessibility  
- Use CSS for styling  
- Support multiple formats  
