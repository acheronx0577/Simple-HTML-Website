[← Back to README](../README.md) · [Next: Final Practical Project →](step-06-practice.md)

# Step 5: Adding Links & Images

A text-only website is a good start, but the web is interactive and visual! In this step, you will learn how to connect pages using links and display images.

---

## 1. Adding Hyperlinks (`<a>`)

To link to another webpage, we use the **`<a>`** tag (which stands for **anchor**).
* It requires the **`href`** attribute (hypertext reference), which specifies the web address you want to visit.
* The text that the user clicks on goes between the opening `<a>` and closing `</a>` tags.

### Code Example:
```html
<a href="https://github.com">Visit my GitHub</a>
```

---

## 2. Embedding Images (`<img>`)

To show a picture on your page, we use the **`<img>`** tag.
* It is a **self-closing tag**, meaning it doesn't need a closing `</img>` tag.
* It requires the **`src`** attribute (source), which specifies the path or URL to the image file.
* It also requires the **`alt`** attribute (alternative text), which describes the image for screen readers or if the image fails to load.

### Code Example:
```html
<img src="images/profile.png" alt="A portrait photo of me smiling">
```

---

## Visual Explanation

Below is an infographic explaining how anchor attributes and image tags work:

![Links and Images Demo](images/links_and_images_demo.png)

---

## Hands-On Exercise

Let's add a placeholder profile picture and some interactive links to your webpage.

Update your `index.html` file with this code block:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Interactive Homepage</title>
  </head>
  <body>

    <!-- Header Section -->
    <div>
      <h1>Jane Doe</h1>
      <p>Web Developer & Learner</p>
    </div>

    <!-- Media Section -->
    <div>
      <!-- Displays a placeholder developer illustration from the web -->
      <img src="https://placehold.co/150" alt="Jane Doe's Avatar Profile Picture">
    </div>

    <!-- Info Section -->
    <div>
      <h2>About Me</h2>
      <p>I enjoy learning new web development skills!</p>
    </div>

    <!-- Contact & Links Section -->
    <div>
      <h2>Find Me Online</h2>
      <p>Check out my online profiles:</p>
      <a href="https://github.com">My GitHub Profile</a> ·
      <a href="https://linkedin.com">My LinkedIn Profile</a>
    </div>

  </body>
</html>
```

### Steps to Test:
1. Copy the code block above into your `index.html` file.
2. Save the file and refresh your browser.
3. Click the links—they should open the corresponding websites!
4. Check the image—you should see a square placeholder box loaded from the internet.

---

[← Back to README](../README.md) · [Next: Final Practical Project →](step-06-practice.md)
