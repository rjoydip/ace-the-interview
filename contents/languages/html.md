# HTML Interview Questions and Answers

**1. What is the basic structure of an HTML document?**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    </body>
</html>
```

**2. What are semantic HTML elements? Give some examples.**

**Answer:** Semantic HTML elements are elements that clearly describe their meaning to both the browser and the developer. They provide structure and context to the content.Examples: `<article>`, `<aside>`, `<nav>`, `<header>`, `<footer>`, `<section>`.

**3. What is the difference between `<div>` and `<span>`?**

**Answer:** Both are container elements.`<div>` is a block-level element, meaning it takes up the full width available and starts on a new line.`<span>` is an inline element, meaning it only takes up as much width as its content and does not start a new line.

**4. What is the purpose of the `<!DOCTYPE html>` declaration?**

**Answer:** The `<!DOCTYPE html>` declaration is used to specify the document type and version of HTML being used.  For HTML5, it is simply `<!DOCTYPE html>`.  It should be the very first thing in your HTML document.

**5. What is the difference between HTML attributes and HTML elements?**

**Answer:** HTML elements are the building blocks of an HTML page, defined by tags (e.g., `<div>`, `<p>`, `<a>`).  HTML attributes provide additional information about HTML elements.  They are specified in the start tag of an element (e.g., `<a href="https://www.example.com">`).

**6. What are the different types of lists in HTML?**

* Ordered Lists (`<ol>`):  Used for lists where the order of items is important (e.g., numbered lists).
* Unordered Lists (`<ul>`): Used for lists where the order of items is not important (e.g., bulleted lists).
* Description Lists (`<dl>`): Used for lists of terms and their descriptions.
