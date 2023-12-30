# Getting Started with CSS
## Contents
[Introduction to CSS](#intro)
[Basic Syntax](#syntax)
[Types of CSS stylesheets](#types)
[HTML Box Tag](#box)
[CSS Selectors](#select)
[CSS Box Model](#bem)
[Project 1: Tribute Page](#pro1)
[Project 2: Product Landing Page](#pro2)
[Project 3: Logistics Company Landing Page](#pro3)
[References](#ref)

## Introduction to CSS <a name="intro"></a>

CSS stands for Cascading Style Sheets. It is a language that describes the presentation of web pages, including colors, layout, and fonts. CSS is used to style HTML elements.

## **Basic CSS syntax:** <a name="syntax"></a>

![Basic CSS syntax](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zbaemea2irax1e0g1lju.png)

* **Selector:** The selector specifies which HTML element you want to style.
* **Property:** The property specifies what CSS property you want to set.
* **Value:** The value specifies the value of the CSS property.

Here is an example of a CSS rule that changes the color of all `<p>` elements to red:
![P](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hv5kch4ao3pidq287jem.png)

## **Types of CSS stylesheets:** <a name="types"></a>

* **Inline CSS:** Inline CSS is used to style individual HTML elements. It is defined using the `style` attribute of the HTML element. 

![Inline](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/du15g4vh28btfar4ns7h.png)

* **Internal or Embedded CSS:** Embedded CSS is defined within the `<head>` section of an HTML document. It is used to style all of the elements in the document.

![Internal or Embedded CSS](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kcjhf2vqmloyf5ndhscw.png)

* **External or Linked CSS:** Linked CSS is defined in a separate CSS file and is linked to an HTML document using the `<link>` tag. It is the most common way to use CSS.

**Example of linked CSS:**

![Example of linked CSS](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/dl6it8l31ztkuei5ns23.png)

This HTML document includes a `<link>` tag that points to a CSS file called `styles.css`. The CSS file contains the following CSS rules:

![Style CSS](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/fcqyioupjwsohtq9tijo.png)
These CSS rules will be applied to the HTML elements in the document, resulting in a webpage with a consistent and visually appealing style.

## DIV and Section Tags <a name="box"></a>

![Box Tags](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/z28ndkvimu2saf88qq8g.png)
**DIV**

The DIV tag is a generic container tag used to group related content together and create a logical structure for a web page. It doesn't have any specific meaning or purpose, but it's often used to create sections, headers, footers, and other layout elements.

**Section**

The Section tag is a semantic container tag used to represent a distinct section of a web page with its own heading, content, and possibly related sub-content. It helps better define the page structure and improves accessibility.

**Other Box Tags**

* **Article:** Represents a self-contained piece of content, like a blog post or news article.

* **Main:** Identifies the dominant content, excluding sidebars or navigation.

* **Aside:** Represents supplementary content related to the main content, like a sidebar or callout box.

* **Nav:** Represents navigational links within a web page.

* **Details:** Represents expandable content, typically with a summary and expanded details.

* **Footer:** Represents the bottom section of a web page, often containing copyright information, contact details, or additional links.

* **Header:** Represents the top section of a web page, often containing the site logo, navigation menu, and search bar.


## CSS Selector <a name="select"></a>
CSS selectors are the building blocks of CSS styling. They allow you to target specific HTML elements and apply styles to them. There are three main types of CSS selectors:

![HTML](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/crw2b1jg28fzv8kcmq8k.png)

**1. ID Selectors**

An ID selector targets an element with a specific ID attribute. IDs must be unique within an HTML document.

Example:

![ID Selector](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hn3yivs48a25h7p0yj57.png)
This CSS rule targets the element with the ID `my-header` and sets its background color to light gray and adds padding.

**2. Class Selectors**

A class selector targets elements with a specific class attribute. Classes can be applied to multiple elements within an HTML document.

Example:

![Class Selectors](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/uuzryz740r2mg49e5rz6.png)

This CSS rule targets all elements with the class `my-paragraph` and sets their font size to 16px and line-height to 1.5.

**3. Element Selectors**

An element selector targets all elements of a specific type.

Example:
![Element Selector](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/sh3rue2hvpr2cahhnqpa.png)

This CSS rule targets all `h1` heading elements and sets their font size to 32px, weight to bold, and adds bottom margin.

**Other CSS Selectors**
While ID, class, and element selectors form the foundation for CSS targeting, there are several other selectors that are more specific.

**Descendant Selectors:**

Descendant selectors target elements nested within other elements. For instance, `div > p` selects all `<p>` elements that are direct children of `<div>` elements.

**Child Selectors:**

Child selectors target only the immediate children of an element. For example, `div .my-paragraph` selects all `<p>` elements with the class `my-paragraph` that are direct children of `<div>` elements.

**Attribute Selectors:**

Attribute selectors target elements based on the presence or value of an HTML attribute. For example, `img[alt]` selects all `<img>` elements that have an `alt` attribute, regardless of its value.

**Pseudo-Classes:**

Pseudo-classes represent states or situations of elements, such as `:hover` for when an element is hovered over. `:active` for when an element is clicked, and `:focus` for when an element is focused.

**Pseudo-Elements:**

Pseudo-elements represent specific parts of an element, such as `::before` for content before the element and `::after` for content after the element.

## The CSS Box Model <a name="bem"></a>
Imagine every element on a web page as a box. This box has four parts.
![BEM](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/e86fzwn0a1t6uvwkbby9.png)
* **Content:** This is the stuff inside the box, like words, images, or videos.

* **Padding:** A transparent space around the content, creates a bit of space between the content and the box's edge.

* **Border:** A visible line around the outside of the box. You can change its color, thickness, and style.

* **Margin:** This is the space around the entire box, keeping it from touching other boxes on the page, separating the element from neighbors.

# Projects
## Project 1: Tribute Page <a name="pro1"></a>

![Tribute Page](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9rh5hwew9s6pe2npfwuf.PNG)
Click [here](https://trinket.io/html/56c4117470) to view the finished project.

Click [here](https://trinket.io/html/9ef1178f61) to start creating yours.

### Summary

- The `<!DOCTYPE html>` declaration indicates the HTML document type.

- The `<html>` tag encloses the entire HTML document.

- The `<head>` section contains metadata and links to external resources.

- The `<meta charset="UTF-8">` tag specifies the character encoding.

- The `<meta name="viewport" content="width=device-width, initial-scale=1.0">` tag ensures responsive design.

- The `<title>Tribute to Albert Einstein</title>` tag sets the page title.

- The `<link rel="stylesheet" href="style.css">` tag links to the external CSS stylesheet.

- The `<body>` section contains the visible content of the page.

- The `<div class="hero-container">` tag creates the main container for the page's content.

- The `<div class="hero-image">` tag holds the image of Albert Einstein.

- The `<img src="Einstein_patentoffice.jpg" alt="Albert Einstein image">` tag displays the image.

- The `<div class="hero-info">` tag holds the biographical information about Einstein.

- The `<h1>Albert Einstein</h1>` tag displays the heading "Albert Einstein".

- The `<p>` tags contain paragraphs of text providing information about Einstein.

- The `<ul>` tag creates an unordered list of Einstein's accomplishments.

- The `<li>` tags represent individual list items within the unordered list.

**CSS Styling:**

- The `body` CSS rules define the overall font and margin/padding settings.

- The `.hero-container` CSS rules set the container's width and clear any floats.

- The `.hero-image` CSS rules position the image on the left, set its width, and center its text.

- The `.hero-info` CSS rules position the biographical information on the right and add padding.

- The `h1` CSS rules set the heading's font size, alignment, and bottom margin.

- The `p` CSS rules set the paragraph's font size and line-height.

- The `ul` CSS rules remove default list styling and set padding and margin to zero.

- The `li` CSS rules add bottom margin to each list item.

- The `img` CSS rules set the image's width to 90% and maintain its aspect ratio.


## Project 2: Product Landing Page<a name="pro2"></a>
Click [here](https://trinket.io/html/43a05ee375) to view the finished project.

![Web dev](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/3st8ta4ymvahamajcit8.PNG)

Click [here](https://trinket.io/html/85341dbcc9) to start creating yours.

### Summary
**HTML Structure:**

- The `<!DOCTYPE html>` declaration indicates the HTML document type.

- The `<html lang="en">` tag encloses the entire HTML document and specifies the language as English.

- The `<head>` section contains metadata and links to external resources.

- The `<title>Web Development Course</title>` tag sets the page title.

- The `<link rel="stylesheet" href="style.css">` tag links to the external CSS stylesheet.

- The `<body>` section contains the visible content of the page.

- The `<header><h1>Web Development Course</h1></header>` creates a simple header with the course title.

- The `<section>` tag holds the main content of the page, including an introduction, course information, a call-to-action button, and an image.

- The `<div class="course-info">` tag divides the course information into two columns.

- The `<div class="cta-button">` tag holds the call-to-action button with an enrollment link.

- The `<footer>` tag provides a simple footer with copyright information.

**CSS Styling:**

- The `body` CSS rules define the font family, margins, padding, and background color for the page.

- The `header` CSS rules set the background color, text color, padding, and text alignment for the header.

- The `section` CSS rules define the maximum width, margins, padding, background color, box-shadow, and border radius for the main content section.

- The `h1` CSS rule sets the color for headings.

- The `p` CSS rule sets the color for paragraphs.

- The `.course-info` CSS rule clears the floats to prevent overlapping content.

- The `.course-info div` CSS rules set the float and width for the two columns within the course information section.

- The `.course-info img` CSS rules set the maximum width and maintain the aspect ratio for the image.

- The `.cta-button` CSS rules define the styling for the call-to-action button, including padding, font size, text alignment, background color, border radius, and transition.

- The `.cta-button a` CSS rules remove text decoration and set the color for the link text.

- The `.cta-button:hover` CSS rule changes the background color of the button on hover.

- The `footer` CSS rules set the background color and text alignment for the footer.

- The `footer p` CSS rule sets the color for the text in the footer.

## Project 3: Logistics Company Landing Page <a name="pro3"></a>
Click [here](https://trinket.io/html/35e06b7527) to view the finished project.

![IB Logistics](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/p2arp0v55fq9pgk8a08a.PNG)
Click [here](https://trinket.io/html/86f3225ac0) to start creating yours.


### Summary
**HTML Structure:**

- The `<!DOCTYPE html>` declaration indicates the HTML document type.

- The `<html lang="en">` tag encloses the entire HTML document and specifies the language as English.

- The `<head>` section contains metadata and a link to an external CSS stylesheet.

- The `<title>IB Logistics</title>` tag sets the page title.

- The `<link rel="stylesheet" href="style.css">` tag links to the external CSS stylesheet.

- The `<body>` section contains the visible content of the page.

- The `<header><h1>IB Logistics🛒</h1></header>` creates a simple header with the company name and logo.

- The `<main>` tag holds the main content of the page, including a tracking section.

- The `<section id="tracking-section">` section groups the tracking form and result elements.

- The `<h2>Track Your Shipment</h2>` heading introduces the tracking functionality.

- The `<form id="tracking-form">` form allows users to enter their tracking code.

- The `<label for="tracking-code">Enter Tracking Code:</label>` label prompts the user to enter their tracking code.

- The `<input type="text" id="tracking-code" name="tracking-code" placeholder="Enter your tracking code" required>` input field accepts the tracking code.

- The `<button type="submit">Track</button>` button triggers the tracking process.

- The `<p id="tracking-result"></p>` paragraph displays the tracking result.

- The `<footer>` tag provides a simple footer with copyright information.

**CSS Styling:**

- The `body` CSS rules define the font family, margins, and padding for the page.

- The `header` CSS rules set the background color, text color, text alignment, and padding for the header.

- The `main` CSS rules limit the maximum width, center the content, and add padding to the main content section.

- The `section` CSS rule adds margin to the tracking section.

- The `label` CSS rule positions the labels for the tracking form.

- The `input` CSS rules style the input fields for the tracking form.

- The `button` CSS rules define the styling for the submit button, including padding, font color, background color, border radius, text transformation, and cursor style.

- The `button:hover` CSS rule changes the background color of the button on hover.

- The `#tracking-result` CSS rule sets the margin and font weight for the tracking result paragraph.

- The `footer` CSS rules set the background color, text color, text alignment, padding, and position (fixed bottom of the page) for the footer.

## References And Resources <a name="ref"></a>

* **CSS Cheat Sheet:** [CSS Cheat Sheet](https://docs.google.com/document/d/e/2PACX-1vThnCjD2mWjAyBdBbjc5UG2uZPlrVaor65J6YS9E0zclCdIlJcR52G_MQ5UnMtXZd9LzOlYwFhYAjkk/pub)

* **CSS Tutorial by W3Schools:** [CSS Tuts](https://www.w3schools.com/css/)

* **Cascading Style Sheets (CSS): A Beginner's Guide by Mozilla Developer Network:** [CSS Beginner's Guide](https://developer.mozilla.org/en-US/docs/Web/CSS)

* **Introduction to CSS by Khan Academy:** [Intro to CSS](https://www.khanacademy.org/computing/computer-programming/html-css/intro-to-css/pt/css-basics)

* **CSS Crash Course by CSS-Tricks:** [CSS Crash Course](https://www.youtube.com/watch?v=yfoY53QXEnI)

* **The Complete CSS Guide by SitePoint:** [The Complete CSS Guide](https://www.sitepoint.com/html-css/html/)

**☕ Enjoyed this article? Support my work with a coffee: [https://www.buymeacoffee.com/cqvuesleq](https://www.buymeacoffee.com/cqvuesleq)**

**Also open for technical writing and frontend dev roles!**
