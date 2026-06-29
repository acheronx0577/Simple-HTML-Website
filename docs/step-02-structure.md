[← Back to README](../README.md) · [Next: Formatting Text →](step-03-text.md)

# Step 2: Basic Document Skeleton

Every standard HTML webpage requires a specific set of tags to help the browser understand the code. Think of this as the "skeleton" or boilerplate code.

In this step, you will write the basic structure of your page. We will use a profile for **Jane Doe** as our course example, which you will gradually build up and can customize with your own details at the end.

---

## The Boilerplate Code

Type this code exactly into your `index.html` file:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Jane Doe - Profile</title>
  </head>
  <body>
    Jane Doe
  </body>
</html>
```

Here is a screenshot of what this code renders in your web browser:

![Browser Render of Skeleton](images/step_02_render.png)

---

## Tag Explanations

Let's break down each element you just typed:

### 1. `<!DOCTYPE html>`
* **What it does:** This is a declaration that tells the web browser that this file is a modern **HTML5** document.
* **Note:** It does not need a closing tag.

### 2. `<html>` and `</html>`
* **What it does:** The root container that wraps all your HTML code. Every tag you write (except the DOCTYPE) must live between `<html>` and `</html>`.

### 3. `<head>` and `</head>`
* **What it does:** Contains metadata about the page. This information is processed by the browser behind the scenes.
* **Important children:** The `<meta charset="utf-8">` and `<title>` tags live inside `<head>`.

### 4. `<meta charset="utf-8">`
* **What it does:** Tells the browser to use **UTF-8 character encoding**. This ensures symbols (like dividers `·`) and special characters render correctly without showing weird text like `Â`.

### 5. `<title>` and `</title>`
* **What it does:** Defines the title of the webpage. This is the text displayed on your browser's tab (e.g., "Jane Doe - Profile").

### 6. `<body>` and `</body>`
* **What it does:** Contains all the visible contents of the website. Anything you want the user to see—text, headers, buttons, layout containers—goes between `<body>` and `</body>`.

---

[← Back to README](../README.md) · [Next: Formatting Text →](step-03-text.md)
