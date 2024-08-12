# Lesson 2: CSS Basics - Styling Rory Gilmore's Profile

## Objective
Learn the basics of CSS and apply styles to the HTML profile page for Rory Gilmore that we created in Lesson 1.

## Concepts Covered
- CSS selectors (element, class, ID)
- Colors and backgrounds
- Fonts and text styling
- Margins and padding
- Basic layout with display property

## Exercise

### Step 1: Create your CSS file
1. In the `02-css-basics` folder, create a new file called `styles.css`.
2. Link this CSS file to your `index.html` by adding the following line inside the `<head>` tag:
   ```html
   <link rel="stylesheet" href="styles.css">
   ```

### Step 2: Style the body and main heading
Add the following CSS to your `styles.css` file, replacing the color values with your own choices:

```css
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 20px;
    background-color: /* Choose a light background color */;
}

h1 {
    color: /* Choose a color that contrasts well with the background */;
    text-align: center;
}
```

### Step 3: Style paragraphs and lists
Add styles for paragraphs and lists:

```css
p {
    color: /* Choose a color that's easy to read on your background */;
    margin-bottom: 15px;
}

ul {
    background-color: /* Choose a color that contrasts with the body background */;
    border: 1px solid /* Choose a border color */;
    border-radius: 5px;
    padding: 15px;
}

li {
    margin-bottom: 5px;
}
```

### Step 4: Style links and images
Add styles for links and images:

```css
a {
    color: /* Choose a color that stands out but is still readable */;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 15px;
}
```

### Step 5: Add classes and IDs
1. In your `index.html`, add a class called "highlight" to one or two important sentences about Rory.
2. Add an ID called "favorite-book" to the paragraph containing Rory's favorite book.
3. Style these in your CSS:

```css
.highlight {
    background-color: /* Choose a color that draws attention, consider using rgba for transparency */;
    padding: 5px;
    border-radius: 3px;
}

#favorite-book {
    font-style: italic;
    border-left: 3px solid /* Choose a color that complements your design */;
    padding-left: 10px;
}
```

### Step 6: Style the table
Add styles for the table you created in the previous lesson:

```css
table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

th, td {
    border: 1px solid /* Choose a border color */;
    padding: 8px;
    text-align: left;
}

th {
    background-color: /* Choose a color that stands out for headers */;
    color: /* Choose a contrasting text color */;
}

tr:nth-child(even) {
    background-color: /* Choose a subtle background color for even rows */;
}
```

### Step 7: Preview your styled webpage
Open your HTML file in a web browser to see how it looks with the new styles.

### Step 8: Experiment and customize
Feel free to experiment with different colors, font sizes, or layouts. Try adding new classes or IDs to elements and styling them.

### Step 9: Test your work
Open the `css-basics-browser-test.html` file in your browser to run the tests and ensure you've completed all required tasks.

## Challenge (Optional)
Create a simple two-column layout for Rory's profile:
1. Put Rory's image and quick facts in a left column.
2. Put the main content (paragraphs, lists) in a right column.
3. Use CSS flexbox to achieve this layout.

## Resources
- [MDN CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [MDN CSS Colors](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value)
- [CSS Color Picker Tool](https://coolors.co/app)

## Tips for Choosing Colors
- Use color picker tools to experiment with different color combinations.
- Consider color psychology: what emotions or ideas do you want to convey with your color choices?
- Ensure sufficient contrast between text and background colors for readability.
- Try using a color scheme based on colors associated with Rory or the show "Gilmore Girls".

Remember, there's no single "correct" color scheme. The goal is to create a visually appealing and readable page while learning about CSS color properties.