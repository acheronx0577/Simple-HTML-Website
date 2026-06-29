[← Step 3: Headings](step-03-headings.md) · [Next: Containers →](step-05-containers.md)

# Step 4: Paragraphs & Styling

Now we will add descriptive text to our page using paragraphs and apply simple inline style tags.

## Paragraphs (`<p>`)

The `<p>` tag is used to write standard paragraphs. The browser automatically adds visual spacing before and after paragraphs.

## Formatting Text (`<em>` and `<strong>`)

We style inline text using simple formatting tags:
* <strong>`<em>` (Emphasis):</strong> Renders text in *italics* (e.g. for subtitles/jobs).
* <strong>`<strong>` (Strong):</strong> Renders text in **bold** (e.g. to emphasize keywords).

---

## Complete Step Code

Update your `index.html` to add the job subtitle, intro text, and about description:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Jane Doe - Profile</title>
  </head>
  <body>
    <h1>Jane Doe</h1>
    <p><em>Creative Developer & Tech Explorer</em></p>
    <p>Welcome to my simple personal space on the web. I build clean, structured websites.</p>
    
    <h2>About Me</h2>
    <p>I focus on <strong>standard web technologies</strong> to make information accessible, clean, and elegant. Here is a breakdown of what I do:</p>
  </body>
</html>
```

---

## Browser Output

![Browser Render of Text Tags](images/step_04_render.png)

---

[← Step 3: Headings](step-03-headings.md) · [Next: Containers →](step-05-containers.md)
