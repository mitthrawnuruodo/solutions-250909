# Lesson Task: Build a 3-Page Website with Links

## Goal
Create a tiny website with 3 pages:
* `index.html` (Home)
* `about.html` (About)
* `contact.html` (Contact)

Each page should have **headings**, **paragraphs**, **links**, **comments**, and **a horizontal rule**, and they should all link to each other so you can navigate around.

## Step 1: Set Up Your Project
1. Open VS Code.
2. Create a new folder called my-website (in your Projects / Repos folder).
3. Inside the folder, create three files:
    * `index.html`
    * `about.html`
    * `contact.html`

## Step 2: Write Your HTML Pages
Here’s a starter template for `index.html`:

<small style="font-size: 0.9rem">

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - My Website</title>
  </head>
  <body>
    <!-- Header with navigation -->
    <header>
      <h1>Welcome to My Website</h1>
      <nav>
        <a href="index.html">Home</a> |
        <a href="about.html">About</a> |
        <a href="contact.html">Contact</a>
      </nav>
    </header>

    <hr>

    <!-- Main content -->
    <main>
      <h2>Home Page</h2>
      <p>This is the homepage of my very first website.</p>
      <p>Use the navigation links above to visit other pages.</p>
    </main>

    <footer>
      <p>&copy; 2025 My Website</p>
    </footer>
  </body>
</html>
```

</small>

Copy this into `index.html`. 

Then, create similar files for `about.html` and `contact.html`, just change:
* The `<title>`
* The `<h2>` heading
* The `<p>` text content

(Keep the header and footer the same, so it feels like one website.)

## Step 3: Run the Website
1. Right-click `index.html` in VS Code → **Open with Live Server**.
2. Your browser should open with the home page.
3. Click the links to navigate to About and Contact pages.

## Step 4: Inspect the Code
1. In your browser, right-click → **Inspect** (or press Ctrl+Shift+I / Cmd+Option+I).
2. Look at the **Elements tab**:
    * Find your <header>, <nav>, <main>, and <footer>.
    * Expand/collapse them to see the structure.
3. Hover over elements in the inspector → notice how the browser highlights the section on the page.
4. Look for your **HTML comments** (`<!-- ... -->`) in the inspector.

## Step 5: Reflection
* Did the navigation links work as expected?
* Can you explain what each section (`header`, `nav`, `main`, `footer`) is for?
* What happens if you change the text inside `<title>` and refresh the page?
* How can comments help you and other developers when reading code?