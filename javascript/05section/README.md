# SECTION 8: Javascript Basic Concepts

## Overview of Javascript

### Javascript

- Javascript is a popular programming language used for building interactive websites.
- It is a clinet-side scripting language that runs in the browser and allows you to add dynamic behavior to web pages.
- Javascript can be used to create interactive forms, validate user input, and update the content of a web page without reloading it.
- Javascript is also used to create animations, games, and other interactive elements on the web.

### Javascript can do

- Form validation
- Pop-ups and alerts
- Image sliders
- Interactive buttons
- Dynamic content updates

### Javascript Basics

- Javascript is a high-level, interpreted programming language.
- It is loosely typed, which means you don't have to decalre the data type of a variable when you create it
- Javascript uses the `var`, `let`, and `const` keywords to declare variables.
- Javscript is case-sensitive, so `myVariables` and `MyVariable` are considered different variables.
- Javascript statements are terminated by a semicolon (`;`).

### Javascript in HTML

- you can include Javascript code in an HTML document using the `<script>` tag.
- The `<script>` tag can be placed in the `<head>` or `<body>` section of an HTML document.
- You can write Javascript code directly in the `<script>` tag or link an external Javascript file using the `src` attribute.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Javascript demo</title>
    <script>
      // Javascript code goes here
      console.log("Hello, world!");
    </script>
  </head>

  <body>
    <h1>Hello, world!</h1>
    <script src="script.js"></script>
  </body>
</html>
```
