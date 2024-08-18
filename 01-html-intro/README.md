# Week 1: Introduction to HTML - Rory Gilmore's Profile

## Setup

1. Open the `week-01-html-intro` folder in Visual Studio Code.
1. Make sure you have the live Server extension installed in VSCode. If not, you can install it from the Extensions view (`Ctrl+Shift+X`). https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer

## Objective
Learn the basic structure of an HTML document and create a simple profile page for Rory Gilmore from the TV show "Gilmore Girls".

## Concepts Covered
- HTML document structure
- Common HTML tags
- Text formatting
- Links and images

## Exercise

### Step 1: Create your HTML file
1. In VSCode, create a new file called `index.html` inside the `01-html-intro` folder.
1. Add the basic HTML structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><!-- Replace me by your title --></title>
</head>
<body>
    <!-- Your content will go here -->
</body>
</html>
```

(The `<!--` line is called a comment, and it won't be displayed in the browser. It's a good way to add notes to your code.)

The head section contains metadata about the document, such as the character set and the viewport settings (basic information about how the text and content should be displayed). The Body section contains the content that will be displayed in the browser.

As you might have noticed a tag starts with `<` and ends with `>`. The content of the tag is placed between the opening and closing tags. For example, `<h1>My Title</h1>` is a heading tag that will display the text "My Title" as a main heading.

### Step 2: Add content to Rory's profile
Add the following elements to your webpage:
1. A main heading (h1) tag with "Rory Gilmore"
1. A paragraph about Rory (use the `<p>` tag)
1. A list of Rory's interests (use the `<ul>` and `<li>` tags)
1. An image of Rory or a book (use the `<img>` tag)
1. A link to Rory's favorite book (use the `<a>` tag)

Be careful: tags have be opened and closed properly. For example, `<p>` tags should be closed with `</p>`.
List tags are a tiny bit more tricky, you probably should look at the documentation: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul

### Step 3: Use text formatting tags
Use the following tags to format your text:
- `<strong>` for bold text
- `<em>` for italicized text
- `<u>` for underlined text

### Step 4: Preview your webpage
Open your HTML file in a web browser to see how it looks.
Click on the `Go Live` button in the bottom right corner of the VSCode window to open your page in a browser. The file will refresh automatically when you save changes.

### Step 5: Test your work
1. Open `html-intro-browser-test.html` in your web browser.
1. You'll see a list of tests. Green items have passed, while red items have failed.
1. If any tests fail, go back to your `index.html` file and make the necessary corrections.
1. Refresh the `html-intro-browser-test.html` page in your browser to run the tests again.
1. Repeat this process until all tests pass.

### Step 6: Commit and push your work
1. Go to the source control extension in VSCode.
1. Create a new commit with the following message: "Complete week 1 exercise: HTML introduction"
1. push your code to your remote repository.

## Challenge (Required)
Add a table with Rory's class schedule at Chilton Preparatory School.

## Resources
- [MDN Web Docs: HTML basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)

## Next Week
We'll learn how to style our HTML using CSS to make Rory's profile more visually appealing.
