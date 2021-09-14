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

<img src="https://slideplayer.com/slide/12828012/78/images/9/HTML+Page+Structure+Below+is+a+visualization+of+an+HTML+page+structure%3A.jpg"
        alt="HTMl page structure image">

| **Note:** The content inside the <body> section (the white area above) will be displayed in a browser. The content inside the <title> element will be shown in the browser's title bar or in the page's tab. |

### HTML History

Since the early days of the World Wide Web, there have been many versions of HTML:

| **Year** | **Version** |
| ---- | -------------------------------------- |
| 1989 | Tim Berners-Lee invented www |
| 1991 | Tim Berners-Lee invented HTML |
| 1993 | Dave Raggett drafted HTML+ |
| 1995 | HTML Working Group defined HTML 2.0 |
| 1997 | W3C Recommendation: HTML 3.2 |
| 1999 | W3C Recommendation: HTML 4.01 |
| 2000 | W3C Recommendation: XHTML 1.0 |
| 2008 | WHATWG HTML5 First Public Draft |
| 2012 | WHATWG HTML5 Living Standard |
| 2014 | W3C Recommendation: HTML5 |
| 2016 | W3C Candidate Recommendation: HTML 5.1 |
| 2017 | W3C Recommendation: HTML5.1 2nd Edition |
| 2017 | W3C Recommendation: HTML5.2 |

---

# HTML editors

### Learn HTML Using Notepad or TextEdit

Web pages can be created and modified by using professional HTML editors.

However, for learning HTML we recommend a simple text editor like Notepad (PC) or TextEdit (Mac).

**Following are a few html editors that I suggest using :**

- Atom
- Notepad++
- Sublime Text
- Visual Studio Code
 
Follow the steps below to create your first web page with Notepad or TextEdit.

- ### Step 1: Open Notepad (PC)

**Windows 8 or later:**

Open the **Start Screen** (the window symbol at the bottom left on your screen). Type **Notepad**.

**Windows 7 or earlier:**

Open **Start > Programs > Accessories > Notepad**

- ### Step 1: Open TextEdit (Mac)

Open **Finder > Applications > TextEdit**

Also change some preferences to get the application to save files correctly. In **Preferences > Format >** choose **"Plain Text"**

Then under "Open and Save", check the box that says "Display HTML files as HTML code instead of formatted text".

**Then open a new document to place the code.**

- ### Step 2: Write Some HTML

Write or copy the following HTML code into Notepad:

```
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>
</html>
```

<img src="https://www.w3schools.com/html/img_notepad.png"
        alt="Notepad Image">

- ### Step 3: Save the HTML Page

Save the file on your computer. Select **File > Save** as in the Notepad menu.

Name the file "**index.html**" and set the encoding to **UTF-8** (which is the preferred encoding for HTML files).

<img src="https://www.w3schools.com/html/img_saveas.png"
        alt="Notepad Image">

| **Tip:** You can use either .htm or .html as file extension. There is no difference, it is up to you. |

- ### Step 4: View the HTML Page in Your Browser

Open the saved HTML file in your favorite browser (double click on the file, or right-click - and choose "Open with").

The result will look much like this:

<img src="https://www.w3schools.com/html/img_chrome.png"
        alt="Result Image">

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