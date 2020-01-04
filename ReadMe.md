# Intro to HTML and CSS
### Tools
* [Glitch.com](https://glitch.com/)
* * Online web page editor
* [W3 Schools](https://www.w3schools.com/)
* * Online tutorials/reference
* * **Try it yourself** feature
* [GitHub](https://github.com/dshaworth)
* * Course Material

HTML is the content, CSS defines how it will look
___
## HTML
[HTML Tutorial](https://www.w3schools.com/html/default.asp)

HTML (Hyper Text Markup Language) is used to build a web page.

HTML uses [**Tags**](https://www.w3schools.com/tags/default.asp) to define areas of page.
### [Intro](https://www.w3schools.com/html/html_intro.asp)
    
    <!DOCTYPE html>
    <html>
      <head>
        <title>Page Title</title>
      </head>
      <body>
        <h1>My First Heading</h1>
        <p>My first paragraph.</p>
      </body>
    </html>

* Goto the **Try it now** link
* Notice how the page renders.
* That's the browser deciding how a page will look without any additional guidance (CSS).


### [Open Glitch](https://glitch.com/)
1. Create Account (if you don't already have one)
2. Create a new **hello-webpage** project
3. View the default **index.html** page.
  
This page is pretty similar to the HTML page we saw on **W3 Schools**, but it does add some CSS.

This line adds CSS to the page.

    <link rel="stylesheet" href="/style.css">
Comment out that line

    <!-- <link rel="stylesheet" href="/style.css"> -->

Now look at how the page renders.  Without those styes, this is how the browser has decided to display the page.
___
## CSS
[CSS Tutorial](https://www.w3schools.com/css/default.asp)

CSS (Cascading Style Sheets) is used to style a page.

Why style?
[Here's what styling can do.](https://www.w3schools.com/css/css_intro.asp)


### [Three ways to add style](https://www.w3schools.com/css/css_howto.asp)
1. Inline      
2. In Page <style></style> tags
3. External File

CSS
* Case sensitive!
* * my-class is NOT the same as My-Class
* Three main types of selectors
  * tag
     * p{ color: green; }
       * Targets all p elements
  *  class
     * .my-class { color: red; }
       * Targets all elements with **class="my-class"** attribute
  * id
    * #my-id { color: blue; }
      * Targets all elements with **id="my-id"** attribute

Links
* [CSS Selectors](https://www.w3schools.com/css/css_selectors.asp)

## Helpful Tips
* CTRL+A - Select All
* CTRL+C - Copy
* CTRL+V - Paste
* CTRL+X - Cut and Copy
* Google Chrome
  * F12 - Developer Tools
    * Elements Tab