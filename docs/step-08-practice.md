[← Step 7: Images](step-07-images.md) · [Back to README](../README.md)

# Step 8: Final Practical Project

We will now build the final premium unstyled profile. We introduce dividers, lists, blockquotes, and tables.

## New Elements

1. <strong>`<hr>` (Horizontal Rule):</strong> Creates a dividing line to separate sections.
2. <strong>`<blockquote>`:</strong> Indents a block of text (e.g. for personal quotes).
3. <strong>`<ul>` & `<li>` (Unordered List):</strong> Creates bulleted lists (e.g. for interests).
4. <strong>`<table>` (Table):</strong> Displays structured columns (`<tr>` rows, `<th>` headers, `<td>` cells).

---

## Final Project Code

Copy this complete code block and save it to your `index.html` file:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My Premium Profile</title>
  </head>
  <body>
    <div>
      <div>
        <h1>Jane Doe</h1>
        <p><em>Creative Developer & Tech Explorer</em></p>
        <p>Welcome to my simple personal space on the web. I build clean, structured websites.</p>
      </div>
      <hr>
      <div>
        <blockquote>
          "Simplicity is the ultimate sophistication." — Leonardo da Vinci
        </blockquote>
      </div>
      <hr>
      <div>
        <img src="docs/images/profile.png" width="150" height="150" alt="Jane Doe's profile avatar">
      </div>
      <div>
        <h2>About Me</h2>
        <p>
          I focus on <strong>standard web technologies</strong> to make information accessible, clean, and elegant. Here is a breakdown of what I do:
        </p>
        <h3>My Core Interests</h3>
        <ul>
          <li><strong>Coding:</strong> Learning HTML structural tags and semantics.</li>
          <li><strong>Designing:</strong> Understanding alignment, whitespace, and readability.</li>
          <li><strong>Exploring:</strong> Investigating browser rendering systems.</li>
        </ul>
      </div>
      <hr>
      <div>
        <h2>My Learning Roadmap</h2>
        <p>Here is my plan for mastering web technologies:</p>
        <table border="1" cellpadding="8" cellspacing="0">
          <thead>
            <tr>
              <th>Technology</th>
              <th>My Status</th>
              <th>Estimated Time</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>HTML (Structure)</td>
              <td>Learning Today!</td>
              <td>1-2 Days</td>
            </tr>
            <tr>
              <td>CSS (Styling)</td>
              <td>Up Next</td>
              <td>1-2 Weeks</td>
            </tr>
            <tr>
              <td>JavaScript (Logic)</td>
              <td>Planned</td>
              <td>3-4 Weeks</td>
            </tr>
          </tbody>
        </table>
      </div>
      <hr>
      <div>
        <h2>Let's Connect</h2>
        <p>If you would like to collaborate or see more of my work, click any of the links below:</p>
        <p>
          <a href="https://github.com">GitHub</a> · 
          <a href="https://linkedin.com">LinkedIn</a> · 
          <a href="mailto:jane@example.com">Email Me</a>
        </p>
      </div>
    </div>
  </body>
</html>
```

---

## Browser Output

![Final HTML Project Preview](images/premium_layout.png)

---

[← Step 7: Images](step-07-images.md) · [Back to README](../README.md)
