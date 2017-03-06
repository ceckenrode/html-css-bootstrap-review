### CSS Intro

* What is CSS?

  * Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language. 

  * HTML describes a web page's structure, CSS describes its presentation. How and where elements on the page should appear.

* How can we include CSS into an HTML page

  * Linking to an external stylesheet by adding a link tag inside of the HTML page's header.

  ```HTML
  <!DOCTYPE html>
  <html lang="en">

  <head>
   <meta charset="UTF-8">
   <title>Hello World</title>
   <link rel="stylesheet" href="style.css">
  </head>

  <body>
   <p>Hello World</p>
  </body>

  </html>
  ```

  * Adding an internal stylesheet to the web page with style tags inside of the head element.

  ```HTML
  <!DOCTYPE html>
  <html lang="en">

  <head>
   <meta charset="UTF-8">
   <title>Hello World</title>
   <style>
     p {
       font-size: 30px;
       text-decoration: underline;
     }
   </style>
  </head>

  <body>
   <p>Hello World</p>
  </body>

  </html>
  ```

  * By using inline styles, where we add CSS as properties to the HTML elements we want to target.

  ```HTML
  <!DOCTYPE html>
  <html lang="en">

  <head>
   <meta charset="UTF-8">
   <title>Hello World</title>
  </head>

  <body>
   <p style="font-size: 30px; text-decoration: underline;">Hello World</p>
  </body>

  </html>
  ```

* What would the CSS for making all of the anchor elements orange (\<a href="https:www.google.com">Google\</a> look like?

```CSS
a {
  color: orange;
}
```

* A CSS rule can be broken down into 3 parts.

```CSS
selector {
  property: value;
}
```

* **selector:** The element(s) we want to target

* **property:** The property we want to modify.

* **value:** What we want to set the value to.
