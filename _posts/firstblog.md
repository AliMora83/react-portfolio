---
date: '2022-07-15T11:50:54.000Z'
title: Build a weather app
tagline: 'HTML, CSS, JavaScript'
preview: This tutorial will show you how to build a weather app using an API
image: /images/test1.png
---

---

## 1) Create a new project in VS Code

**Visual Studio Code** is an open-source, cross-platform text and code editor. It runs on Windows, macOS and Linux. You can use VS Code to create a new project from the command palette (Ctrl+P) or create a new project with the New Project extension.

## 2) Build HTML Markup

**HyperText Markup Language or HTML** is the standard markup language for documents designed to be displayed in a web browser. When writing HTML, you add "tags" to the text in order to create the structure. These tags tell the browser how to display the text or graphics in the document.

###### Copy this HTML Markup to your VS Code

```jsx
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather API</title>
</head>
<body>
    <form action="/" method="post">
        <label for="cityInput">City Name: </label>
        <input type="text" id="cityInput" name="cityName"
        placeholder="City name here">
        <button type="submit">Send</button>
    </form>
</body>
</html>
```
---

## 3) Build CSS Stylesheet
CSS stands for **Cascading Style Sheets**. It is the language for describing the presentation of Web pages, including colours, layout, and fonts, thus making our web pages presentable to the users.

###### Copy this CSS Style to your VS Code

```jsx
.body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    font-family: 'Open Sans', sans-serif;
    font-size: 120%;
    background-repeat: no-repeat;
    background-size: cover;
  }


  .card {
    background: #000000d0;
    color: white;
    padding: 2em;
    border-radius: 30px;
    width: 100%;
    max-width: 420px;
    margin: 1em;
  }
  
  .search {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
```
---


## Languages you will use:

1. HTML
2. CSS
3. Javascript

---

## Link

Visit the [Weather App](https://openmindi.co.za/weather.html).

---

## Weather App image

![Weather App image](/images/test1.png)

---
