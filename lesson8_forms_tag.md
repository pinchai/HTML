# HTML Forms

HTML forms are used to collect user input. This input is usually sent to a server for processing.

## Basic Syntax

```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" />

  <input type="submit" value="Submit" />
</form>
```

---

# HTML Form Attributes

| Attribute    | Description                 | Example           |
| ------------ | --------------------------- | ----------------- |
| action       | URL where form data is sent | action="/submit"  |
| method       | HTTP method (GET or POST)   | method="post"     |
| target       | Where to display response   | \_blank, \_self   |
| autocomplete | Enable/disable autofill     | autocomplete="on" |
| novalidate   | Disable validation          | <form novalidate> |

---

# HTML Form Elements

| Element    | Description        |
| ---------- | ------------------ |
| <input>    | Input field        |
| <label>    | Label for input    |
| <textarea> | Multi-line input   |
| <select>   | Dropdown list      |
| <option>   | Dropdown item      |
| <button>   | Clickable button   |
| <fieldset> | Group inputs       |
| <legend>   | Title for fieldset |

---

# HTML Input Types

| Type     | Description      |
| -------- | ---------------- |
| text     | Single-line text |
| password | Hidden text      |
| email    | Email input      |
| number   | Numeric input    |
| date     | Date picker      |
| radio    | Single choice    |
| checkbox | Multiple choice  |
| file     | Upload file      |
| submit   | Submit form      |
| reset    | Reset form       |

---

# HTML Input Attributes

| Attribute   | Description       |
| ----------- | ----------------- |
| value       | Default value     |
| placeholder | Hint text         |
| required    | Must be filled    |
| readonly    | Cannot edit       |
| disabled    | Disabled input    |
| maxlength   | Max characters    |
| min / max   | Range for numbers |
| pattern     | Regex validation  |

---

# HTML Input form\* Attributes

| Attribute   | Description          |
| ----------- | -------------------- |
| form        | Link input to a form |
| formaction  | Override form action |
| formmethod  | Override method      |
| formtarget  | Override target      |
| formenctype | Encoding type        |

---

# Mini Quiz

1. What is the difference between GET and POST?
2. Which input type is used for passwords?
3. What does the required attribute do?
4. Which element creates a dropdown list?
5. What is the purpose of <label>?

---

# Practice Tasks

## Task 1: Simple Login Form

Create a form with:

- Username
- Password
- Submit button

## Task 2: Registration Form

Include:

- Name (text)
- Email (email)
- Age (number)
- Gender (radio)
- Hobbies (checkbox)
- Submit button

## Task 3: Advanced Form

Create a form with:

- File upload
- Date picker
- Dropdown (country)
- Validation (required + pattern)
- Custom submit button with formaction
