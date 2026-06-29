[← Back to README](../README.md)

# Step 6: Final Practical Project

Congratulations on making it to the final step! You have learned the basic structure and layout tools of HTML. 

Now, it is time to combine everything into a complete, clean personal homepage that describes who you are. We will use a structure that feels **premium and organized**, relying purely on browser defaults.

---

## What the Webpage Will Look Like

Below is a preview of the final webpage rendered in a browser. By using sections, horizontal rules, lists, blockquotes, and tables, we create a very clean and readable layout without writing a single line of CSS:

![Final HTML Project Preview](images/premium_layout.png)

---

## New Layout Elements

To achieve a premium layout, we are adding four new tags in this final project:
1. **`<hr>` (Horizontal Rule):** Creates a thin horizontal divider line to break the page into separate visual sections.
2. **`<blockquote>`:** Indents a text block, highlighting a quote or personal motto.
3. **`<ul>` & `<li>` (Unordered List):** Creates a neat bulleted list of items (like core interests or skills).
4. **`<table>` (Table):** Allows you to display tabular data using rows (`<tr>`), header cells (`<th>`), and standard data cells (`<td>`).

---

## Final Project Code Block

Copy this complete code block and use it to replace all contents inside your `index.html` file. Make sure to replace the placeholder information (like names, bio texts, and links) with details about yourself.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Premium Profile</title>
  </head>
  <body>

    <!-- Main Wrapper to group everything -->
    <div>
      
      <!-- Header Section -->
      <div>
        <h1>Jane Doe</h1>
        <p><em>Creative Developer & Tech Explorer</em></p>
        <p>Welcome to my simple personal space on the web. I build clean, structured websites.</p>
      </div>

      <hr>

      <!-- Featured Quote Section -->
      <div>
        <blockquote>
          "Simplicity is the ultimate sophistication." — Leonardo da Vinci
        </blockquote>
      </div>

      <hr>

      <!-- Profile Image Section -->
      <div>
        <!-- A placeholder profile avatar image -->
        <img src="https://placehold.co/150" alt="Jane Doe's profile avatar">
      </div>

      <!-- About Me & Skills Section -->
      <div>
        <h2>About Me</h2>
        <p>
          I focus on standard web technologies to make information accessible, clean, and elegant. Here is a breakdown of what I do:
        </p>
        
        <h3>My Core Interests</h3>
        <ul>
          <li><strong>Coding:</strong> Learning HTML structural tags and semantics.</li>
          <li><strong>Designing:</strong> Understanding alignment, whitespace, and readability.</li>
          <li><strong>Exploring:</strong> Investigating browser rendering systems.</li>
        </ul>
      </div>

      <hr>

      <!-- Learning Roadmap Section (Structured using a clean Table) -->
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

      <!-- Connect & Links Section -->
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

## Wrap-Up & Next Steps

You've built your very first webpage! You now know how to:
1. Initialize an HTML document.
2. Structure information with invisible section divs.
3. Form headers and write paragraph texts.
4. Render pictures, build tables, and write quotes.
5. Create clickable links to connect pages and resources.

### What is Next?
HTML represents the **bones** of a website. To make websites look modern, colorful, and styled with custom alignments, your next step is to learn **CSS (Cascading Style Sheets)**.

---

[← Back to README](../README.md)

