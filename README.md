# fake-business

## Fake Business Website Tutorial
Greetings business owner! This manual will walk you through the steps to create a website for your business using HTML and CSS!

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Step-by-Step Guide](#step-by-step-guide)
  - [1. Think Of Ideas!](#brainstorm)
  - [2. Create the CSS File](#2-create-the-css-file)
  - [3. Create the JavaScript File](#3-create-the-javascript-file)
  - [4. Link the CSS and JavaScript Files](#4-link-the-css-and-javascript-files)
  - [5. Open the HTML File in a Browser](#5-open-the-html-file-in-a-browser)
- [Things to Look Out For](#things-to-look-out-for)
- [Conclusion](#conclusion)

## Introduction
In this manual, you will learn more about HTML, CSS -- including **flexbox** -- with the use of making your own business website!

Here's a simple example of the result, there are some extra stuff you can do if you are fast!
![readme-img1](https://github.com/user-attachments/assets/31037174-e788-4fb6-bff0-7f0ae2689297)

## Prerequisites
Before you start, here's a review of CSS Flexbox -- skip if you already know!
- Imagine there is a big box -- let's call it `bigBox` -- and inside, it contains the following: `box1`, `box2`, and `box3`.
  - `bigBox` is the **parent element**.
  - `box1`, `box2`, and `box3` are the **child elements**.
- **Why this is important:** The main idea of this is just elements inside of elements, which is what you'll see a lot of in this manual.

## Project Structure
Here's how the project is structured.
```plaintext
fake-business/
├── index.html
├── thankyou-page.html
└── style.css
The following files you can just leave as is: README.md & image-examples.
```

## Step-by-Step Guide

### 1. Brainstorm!

Before programming your website, think of the following:
- Name of business
- What are you selling?

### 2. Create the CSS File

Create a file named `styles.css` and add the following code to style your webpage:

```css
body {
  font-family: Arial, sans-serif;
}
```

### 3. Create the JavaScript File

Create a file named `script.js` 

### 4. Link the CSS and JavaScript Files

Ensure that the CSS and JavaScript files are linked correctly in your `index.html` file. The `<link>` tag for CSS should be inside the `<head>` section, and the `<script>` tag for JavaScript should be just before the closing `</body>` tag.

### 5. Open the HTML File in a Browser

Open your `index.html` file in a web browser to see your simple website in action. You should see a styled heading, a paragraph, and a button that displays an alert when clicked.

## Things to Look Out For

- Ensure the file paths in the `<link>` and `<script>` tags are correct.
- Use proper HTML structure and semantics.
- Keep your CSS organized and use meaningful class names.
- Avoid inline styles and JavaScript as much as possible for better maintainability.
- Test your website in different browsers to ensure compatibility.

## Stretch Goals
If you finish early, feel free to try out these additions to your website!

### 6. Make it a Header!
Enclose the "Hello World!" in an ``<h1>`` tag as shown here:
```<h1> Hello World! </h1>```
<br>
The full code should now look like this:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1> Hello World! </h1>
  <script src="script.js"></script>
</body>
</html>
```


## Conclusion

Congratulations! You've created a simple website using HTML, CSS, and JavaScript. This is just the beginning – there are many more features and technologies to explore. Keep learning and experimenting to build more complex and dynamic websites.

Feel free to reach out if you have any questions or feedback. Happy coding!
