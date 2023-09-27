# Fullstack Engineering Reference Sheet

## Table of contents

- [What is Full stack devlopment?](##What-is-Full-stack-devlopment?)
- [HTML](#HTML)
- [CSS](#CSS)
- [Javascript](#JavaScript)

    ## What is Full stack devlopment?

    Full stack development is the development of both front end and back end of a website or Web application. Front end is the part of the website that the user interacts with and back end is the part of the website that the user does not see. As a full stack engineer it is important to know both front end and back end technologies in order to create solutions for a client or any problem that you are trying to solve. In fact, full stack engineering is one of the most in demand jobs in the tech industry given that you have to know a very wide range of technologies and tools. In this repository are some of the technologies that you need to know in order to be a full stack engineer and how to use them. We'll be getting into frontend development, backend development and databases, in the future we might even get into devops, cloud computing, mobile app development and even machine learning and AI. So stay tuned for that. If you're interested give this repository a star and follow me on [Github](https://github.com/UbaidRussell). I'll be updating this repository regularly with new content. So let's get started.

    ## HTML

HTML is a markup language that is used to create the structure of a website. HTML stands for Hyper Text Markup Language. This language is used to make the skeleton of a website. It is the foundation of all websites on the internet. It creates things like the headings, paragraphs, lists, tables, forms, images, videos, audios, links, buttons and much more. HTML is the first thing that you need to learn in order to become a full stack engineer. HTML is a very easy  to learn and it is very easy to understand and use. When a website is made with nothing but HTML, it looks like [this](https://info.cern.ch/hypertext/WWW/TheProject.html): ![This is the first website that was ever created and it was made with HTML only.](./images/Webiste%20with%20only%20HTML.png)

<details>
<summary width="80vw"> You can use this dropdown to direct yourself to the section of HTML you want to learn about.</summary>

- [The HTML Document](https://github.com/UbaidRussell/fullstack-engineering-reference-sheet#the-html-document)
- [The heading Element in HTML](https://github.com/UbaidRussell/fullstack-engineering-reference-sheet#the-heading-element-in-html)
- [The Paragraph Element in HTML](https://github.com/UbaidRussell/fullstack-engineering-reference-sheet#the-paragraph-element-in-html)
- [The List Element in HTML](https://github.com/UbaidRussell/fullstack-engineering-reference-sheet#the-list-element-in-html)
- [The Image Element in HTML](https://github.com/UbaidRussell/fullstack-engineering-reference-sheet#the-image-element-in-html)
- [Anchor Element in HTML](https://github.com/UbaidRussell/fullstack-engineering-reference-sheet#the-anchor-element-in-html)
- [The Div Element in HTML](https://github.com/UbaidRussell/fullstack-engineering-reference-sheet#this-is-a-heading)
- [The Span Element in HTML](https://github.com/UbaidRussell/fullstack-engineering-reference-sheet#the-span-element-in-html)
</details>

### The HTML Document

The HTML document is the main file of the website. It is the file that contains all the HTML code of the website when getting started with HTML, the first thing you need to do is create an HTML document. Here is an example of an HTML document:

```html
<!DOCTYPE html> <!--First Line-->
<html lang="en"> <!--Second Line-->
<head> <!--Third Line-->
    <!--This is where we out our meta data-->
    <meta charset="UTF-8">
    <title>My Website</title> <!--Fourth Line-->
</head>
<body> <!--Fifth Line-->
    <!--This is where we put our HTML elements-->
    <h1>This is a heading</h1>
    <p>This is a paragraph</p> 
</body>
</html>
```
What's happening here?
- The first line of the code is the doctype declaration. This tells the browser that this is an HTML document.
- The second line of the code is the html element. This is the root element of the HTML document. This element contains all the other elements of the HTML document.
- The third line of the code is the head element. This element contains all the meta data of the HTML document. The meta data is the data that is not visible to the user. It contains things like the title of the document, the character set of the document and much more.
- The fourth line of the code is the title element. This element contains the title of the document. The title of the document is the text that is displayed on the tab of the browser.
- The fifth line of the code is the body element. This element contains all the visible elements of the HTML document. It contains things like the headings, paragraphs, lists, tables, forms, images, videos, audios, links, buttons and much more.

### The heading Element in HTML
As you can see in the image above, the first thing we see on the page before everything is the heading, in HTML we use the heading element to create a heading. There are 6 different heading elements in HTML. They are h1, h2, h3, h4, h5 and h6. The h1 element is the biggest heading and the h6 element is the smallest heading. The h1 element is used for the main heading of the page and the h2 element is used for the sub heading of the page and so on. Here is an example of how to use the heading element in HTML:

```html
<h1>This is the h1 heading</h1>
<h2>This is the h2 heading</h2>
<h3>This is the h3 heading</h3>
<h4>This is the h4 heaing</h4>
<h5>This is the h5 heading</h5>
<h6>This is the h6 heading</h6>
```
This outputs the following result:
<h1>This is the h1 heading</h1>
<h2>This is the h2 heading</h2>
<h3>This is the h3 heading</h3>
<h4>This is the h4 heaing</h4>
<h5>This is the h5 heading</h5>
<h6>This is the h6 heading</h6>


### The Paragraph Element in HTML

The paragraph element is used to create a paragraph in HTML. It is used to write text in a paragraph. Here is an example of how to use the paragraph element in HTML:

```html 
<p>This is a paragraph</p>
```
This outputs the following result:
<p>This is a paragraph</p>

### The List Element in HTML
Let's say you want to create a list of items, you can use the list element in HTML to create a list. There are two types of lists in HTML, they are ordered lists and unordered lists. Ordered lists are lists that are numbered and unordered lists are lists that are not numbered. Here is an example of how to use the list element in HTML:

```html 
<h2>Ordered List</h2>
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>  

<h2>Unordered List</h2>
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```
This outputs the following result:
<h2>Ordered List</h2>
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
<h2>Unordered List</h2>
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>

### The Image Element in HTML
The image element is used to add an image to a website. Here is an example of how to use the image element in HTML:

```html
<img src="https://images.pexels.com/photos/667211/pexels-photo-667211.jpeg" alt="This is an image">
```
This outputs the following result:
<img src="https://images.pexels.com/photos/667211/pexels-photo-667211.jpeg" alt="This is an image">

### The Anchor Element in HTML
The anchor element is used to create a link in HTML. Here is an example of how to use the anchor element in HTML:

```html
<a href="https://www.google.com">This is a link</a>
```
This outputs the following result:
<a href="https://www.google.com">This is a link</a> (Goes to google.com)


### The Div Element in HTML
The div element is used to create a division in HTML. It is used to group elements together. Here is an example of how to use the div element in HTML:

```html
<div>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
</div>
```
This outputs the following result:
<div>
    <h1>This is a heading</h1>
    <p>This is a paragraph</p>
</div>

You see, the div element isn't like other elements, it doesn't have any special properties, it is just used to group elements together. It is used to group elements together so that you can style them together. We'll get into styling in the CSS section.

### The Span Element in HTML
The span element is used to create a span in HTML. It is used to group elements together. Here is an example of how to use the span element in HTML:

```html
<span>
    <p>This is a paragraph</p>
</span>
```
This outputs the following result:
<span>
    <p>This is a paragraph</p>
</span>

You see, the span element isn't like other elements, it doesn't have any special properties, it is just used to group elements together. It is used to group elements together so that you can style them together. We'll get into styling in the CSS section.