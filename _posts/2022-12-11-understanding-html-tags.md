---
layout: post
title: "Understanding HTML Tags: The Building Blocks of Web Pages"
date: '2022-12-11 17:57:36 +0600'
categories: [Programming, HTML]
tags: [programming, html, fullstack]
---

HTML tags are the building blocks of HTML, providing the structure and formatting for web pages. These tags are labels surrounded by angle brackets, and are used to indicate the type and purpose of the content on a page. HTML tags are essential for creating effective and engaging web pages, and are used in conjunction with other technologies such as CSS and JavaScript to create dynamic and interactive content.

### Examples of HTML Tags

#### `<!DOCTYPE>` Defines the Document Type

The `<!DOCTYPE>` tag is used in HTML to declare the type of document being used. This is important because it tells the web browser which version of HTML the page is written in, and allows the browser to interpret and render the page correctly.

For example, the following code uses the `<!DOCTYPE>` tag to declare that the document is written in HTML5:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
  </head>
  <body>
    <h1>Welcome to my website!</h1>
  </body>
</html>
```

It is important to note that the `<!DOCTYPE>` tag is not an HTML tag, but a special instruction that is placed at the beginning of an HTML document. It does not have an opening or closing tag, and is not placed inside the `<html>` tag. Instead, it stands alone on the first line of the HTML document, before any other HTML elements.

#### `<p>`  Paragraph Tag

The `<p>` tag in HTML is used to create a paragraph of text. This tag is often used to contain longer blocks of text, and can be used in conjunction with other HTML elements, such as `<strong>` and `<em>`, to add emphasis or structure to the text.

For example, the following code creates a simple paragraph of text:

```html
<p>This is a paragraph of text.</p>
```

The `<p>` tag can also be used to specify the alignment of the text within the paragraph, using the `align` attribute. For example, the following code creates a paragraph of text that is centered on the page:

```html
<p align="center">This is a paragraph of text that is centered on the page.</p>
```

In addition, the `<p>` tag can be used in conjunction with other HTML elements to create more complex and structured content. For example, the following code creates a paragraph of text that includes a hyperlink and bolded text:

```html
<p>This is a paragraph of text that includes a <a href="https://www.example.com">hyperlink</a> and <strong>bolded text</strong>.</p>
```

Overall, the `<p>` tag is a versatile and important element in HTML, and is widely used in creating the content of a webpage.

#### `<h1>` Heading Tag

The `<h>` tag in HTML is used to create a heading of a specific size. The `<h>` tag comes in six different sizes, ranging from `<h1>` to `<h6>`, with `<h1>` being the largest and `<h6>` being the smallest. This tag is used to organize and structure the content of a webpage, and can be used to create a hierarchy of information.

For example, the following code:

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Sub-subheading</h3>
```

The `<h>` tag can also be used in conjunction with other HTML elements, such as `<strong>` and `<em>`, to add emphasis or structure to the text. For example, the code:

```html
<h2>Important Subheading: <strong>Do not ignore!</strong></h2>
```

#### `<a>` Hyperlink Tag

The `<a>` tag in HTML is used to create a hyperlink to another webpage. This tag is often referred to as the anchor tag, and it is used to link to other pages within the same website, or to external websites. The `<a>` tag requires an `href` attribute, which specifies the URL of the target webpage, as well as anchor text, which is the text that is displayed as the link. For example:

```html
<a href="https://www.google.com/">Visit our website</a>
```

In this code example, the `<a>` tag is used to create a hyperlink to the website "[https://www.google.com/](https://www.google.com/)". The anchor text is "Visit our website", which is the text that will be displayed and clickable on the webpage. When a user clicks on this link, they will be redirected to the specified URL. The `<a>` tag is an important part of creating a user-friendly and navigable website.

#### `<button>` Button Tag

The `<button>` tag in HTML is used to create a clickable button on a webpage. The button can be used to trigger an action, such as submitting a form, opening a new page, or running a JavaScript function. The `<button>` tag can be used in combination with other HTML elements, such as `<form>` and `<input>`, to create interactive and user-friendly webpages.

For example, the following code creates a simple button that says "Click me!" and runs a JavaScript function when clicked:

```html
<button onclick="myFunction()">Click me!</button>
```

When the button is clicked, the JavaScript function `myFunction()` will be executed. This could be used to perform a variety of actions, such as displaying an alert message, changing the content of the page, or sending data to a server. The `<button>` tag is a versatile and useful tool for creating interactive webpages.

### Here is a list of some common HTML tags and their usage

<table style="word-wrap"><colgroup>
<col width="20%" />
<col width="80%" />
</colgroup><thead><tr><th>Tag</th><th>Usage</th></tr></thead><tbody><tr><td><code>&lt;html&gt;</code></td><td>The main container for all the content on a webpage. Tells the web browser that the document is written in HTML, and encloses all the other HTML elements on the page.</td></tr><tr><td><code>&lt;head&gt;</code></td><td>Contains the metadata for a webpage, such as the title, keywords, and stylesheets.</td></tr><tr><td><code>&lt;title&gt;</code></td><td>Specifies the title of a webpage, which is displayed in the title bar of the web browser.</td></tr><tr><td><code>&lt;body&gt;</code></td><td>Contains the main content of a webpage, such as text, images, videos, and other multimedia elements.</td></tr><tr><td><code>&lt;h1&gt;-&lt;h6&gt;</code></td><td>Used to create headings of different sizes, with <code>&lt;h1&gt;</code> being the largest and <code>&lt;h6&gt;</code> being the smallest. Organizes and structures the content of a webpage.</td></tr><tr><td><code>&lt;p&gt;</code></td><td>Used to create a paragraph of text. Often used to contain long blocks of text, and can be used in conjunction with other HTML elements to add emphasis or structure.</td></tr><tr><td><code>&lt;img&gt;</code></td><td>Inserts an image onto a webpage. Requires a <code>src</code> attribute, which specifies the location of the image file, as well as optional <code>alt</code> and <code>title</code> attributes.</td></tr><tr><td><code>&lt;a&gt;</code></td><td>Used to create a hyperlink to another webpage. Requires an <code>href</code> attribute, which specifies the URL of the target webpage, as well as anchor text.</td></tr><tr><td><code>&lt;ul&gt;</code></td><td>Used to create an unordered list, in which the items are displayed with bullet points.</td></tr><tr><td><code>&lt;ol&gt;</code></td><td>Used to create an ordered list, in which the items are displayed with numbers or letters.</td></tr><tr><td><code>&lt;li&gt;</code></td><td>Used to create an individual item within a list.</td></tr><tr><td><code>&lt;button&gt;</code></td><td>Used to create a clickable button on a webpage. Can be used to trigger an action, such as submitting a form, opening a new page, or running a JavaScript function.</td></tr></tbody></table>

These are just a few examples of the many different HTML tags that are available. There are many more tags that can be used to add additional functionality and features to a webpage.

There are many additional HTML tags that can be used in creating a webpage. Here is link containing all the HTML tags:

[All HTML Tags](https://www.w3schools.com/TAGS/default.asp){:target="_blank"}
