# HTML/CSS Review

This is a review of your working knowledge of HTML and CSS. Note that this review is designed to help you recall and familiarize yourself with technical concepts.

## Getting Started

* Fork and clone this repository
* Answer the following questions by...
  * Opening this file in Sublime
  * Answering the questions via Markdown. Feel free to refer to this [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Commit your changes
* Make a pull request for submission

---

## HTML

1.) Create a valid, empty HTML page with the necessary tags.

```html
<!-- <!DOCTYPE html>
<head></head>
<body>
</body>
</html> -->
```

2.) What are the differences between these tags?

```html
<!-- self closing tag -->
<img src="images/me.jpg" alt="My profile image">

<!-- has an opening and closing tag -->
<div></div>
```

```
Explain here.
```

---

## CSS

1.) Compare and contrast the following ways to add CSS to HTML elements.

```html
<!-- inline has the highest priority, which means that it will override a style defined inside the <head> tag, or in an external style sheet, or a browser default value. -->
<div style="background-color: red;"></div>

<!-- internal style sheet is a section on an html that contains style definitions. they are assoicated with the <style> tag within the <head> area of the doc. -->
<style type="text/css">
  div {
    background-color: red;
  }
</style>

<!-- External style sheet is used when you link your html with a css style sheet. You then call the element in the style sheet to style it. -->
<link rel="stylesheet" type="text/css" href="css/style.css">
```

```
Explain here
```

2.) Below are some different CSS selectors. Use CSS comments to describe what each selector will do.

```css
/* will round the borders on all the divs */
div {
  border-radius: 50%;
}

/* font of header paragraph within the .header class */
.header p {
  font-size: 18px;
}

/* position of the class .footer */
.footer {
  position: absolute;
  bottom: 0;
}

/* image on page */
.splash-image {
  background-image: url("../images/ocean.jpg");
  background-size: cover;
  width: 100%;
}

/* an action when item in .ninja is hovered over */
.ninja:hover {
  display: none;
  color: black;
}
```



