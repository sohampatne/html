<h1> HTML - Hyper Text Markup Lanuguage </h1>

# Introduction

## What is HTML?

- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

### Example

``` 
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
 ```

### Example Explained

- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document
- The `<html>` element is the root element of an HTML page
- The `<head>` element contains meta information about the HTML page
- The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The `<h1>` element defines a large heading
- The `<p>` element defines a paragraph

## What is an HTML Element?
An HTML element is defined by a start tag, some content, and an end tag:

` <tagname>Content goes here...</tagname> `
The HTML element is everything from the start tag to the end tag:

` <h1>My First Heading</h1> `
` <p>My first paragraph.</p> `

| **Start Tag**  | **Element Content** | **End Tag** |
| -------------- | ------------------- | ----------- | 
| `<h1>` | My First Heading | `</h1>` |
| `<p>` | My first Paragraph | `</p>` |
| `<br>` | _none_ | _none_ |

| **Note:** Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag! |

## Web Browsers

The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.
A browser does not display the HTML tags, but uses them to determine how to display the document:

<img src="https://www.w3schools.com/html/img_chrome.png"
        alt="Chrome Image">

## HTML Page Structure

Below is a visualization of an HTML page structure:

<div style="width:99%;border:1px solid grey;padding:3px;margin:0;background-color:#ddd">&lt;html&gt;
<div style="width:90%;border:1px solid grey;padding:3px;margin:20px">&lt;head&gt;
<div style="width:90%;border:1px solid grey;padding:5px;margin:20px">&lt;title&gt;Page title&lt;/title&gt;
</div>
&lt;/head&gt;
</div>
<div style="width:90%;border:1px solid grey;padding:3px;margin:20px;background-color:#ddd">&lt;body&gt;
<div style="width:90%;border:1px solid grey;padding:3px;margin:20px;background-color:#fff">
<div style="width:90%;border:1px solid grey;padding:5px;margin:20px">&lt;h1&gt;This is a heading&lt;/h1&gt;</div>
<div style="width:90%;border:1px solid grey;padding:5px;margin:20px">&lt;p&gt;This is a paragraph.&lt;/p&gt;</div>
<div style="width:90%;border:1px solid grey;padding:5px;margin:20px">&lt;p&gt;This is another paragraph.&lt;/p&gt;</div>
</div>
&lt;/body&gt;
</div>
&lt;/html&gt;
</div>

---

# Basics

### HTML Documents

All HTML documents must start with a document type declaration: `<!DOCTYPE html>`.

The HTML document itself begins with `<html>` and ends with `</html>`.

The visible part of the HTML document is between `<body>` and `</body>`.

### The <!DOCTYPE> Declaration

The `<!DOCTYPE>` declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The `<!DOCTYPE>` declaration is not case sensitive.

### HTML Headings

HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading.

### HTML Paragraphs

HTML paragraphs are defined with the `<p>` tag

### HTML Links

HTML links are defined with the `<a>` tag.

### HTML Images

HTML images are defined with the `<img>` tag.

The source file `(src)`, alternative text `(alt)`, width, and height are provided as attributes

#### How to View HTML Source?

Have you ever seen a Web page and wondered "Hey! How did they do that?"

##### View HTML Source Code:

Right-click in an HTML page and select "View Page Source" (in Chrome) or "View Source" (in Edge), or similar in other browsers. This will open a window containing the HTML source code of the page.

##### Inspect an HTML Element:

Right-click on an element (or a blank area), and choose "Inspect" or "Inspect Element" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel