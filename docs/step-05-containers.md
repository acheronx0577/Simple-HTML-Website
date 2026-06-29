[← Step 4: Paragraphs](step-04-paragraphs.md) · [Next: Adding Links →](step-06-links.md)

# Step 5: Structuring with Containers

As pages grow, we organize layout elements using container divisions called **`<div>`** tags.

## What is a `<div>`?

The **`<div>`** (division) tag groups block-level elements together:
* It is a **block-level container**, meaning it starts on a new line and spans the full width of the page.
* It is completely **invisible** by default, acting as a parent wrapper box for child elements.

---

## Stacking Containers

Think of `<div>` tags as invisible boxes stacked vertically on top of each other:

![Div Container Stack Diagram](images/divs_visual_box.png)

Because they are invisible structure markers, adding them does **not** change the visual look in the browser yet:

![Browser Render of Div Containers](images/step_05_render.png)

---

## Complete Step Code

Wrap your header elements and your about elements in parent `<div>` elements:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Jane Doe - Profile</title>
  </head>
  <body>

    <!-- Header Section -->
    <div>
      <h1>Jane Doe</h1>
      <p><em>Creative Developer & Tech Explorer</em></p>
      <p>Welcome to my simple personal space on the web. I build clean, structured websites.</p>
    </div>

    <!-- About Section -->
    <div>
      <h2>About Me</h2>
      <p>I focus on <strong>standard web technologies</strong> to make information accessible, clean, and elegant. Here is a breakdown of what I do:</p>
    </div>

  </body>
</html>
```

---

[← Step 4: Paragraphs](step-04-paragraphs.md) · [Next: Adding Links →](step-06-links.md)
