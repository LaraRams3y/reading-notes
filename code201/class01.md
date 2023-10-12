# Class 01 Reading Notes

## Topic 1 - Getting Started
In this reading, we skimmed through a brief description of how the Web works. Read a recap about the process of designing a website. We also read through some JavaScript basics. While the "how it works" reading indicated that it wasn't significant that a beginning developer fully understand how the Web works, it did suggest that this would be more and more relevant to us. I found it very interesting and somewhat graspable. I'm excited to gain more clarity as I move forward in this field. The description of the website design process was very straightforward and familiar as per what we learned in 102. It makes sense to begin with a basic sketch/outline any time one wants to build anything, whether a garment or a home or a website. The JavaScript basics were a great refresher regarding the JavaScript that we covered in 102, and I am intrigued to find how much farther we will take it with 201.

**HTTP Haiku**  
Transfer protocol.  
Language defined. Clients and   
servers speak. Seamless.  

**How are HTML, CSS, and JS files “parsed” in the browser?**  
The HTTP send the request to the server for approval of access to the address. Once given the ok, the file information is sent in "small stat packets." When working through HTML, CSS, and JS files, HTML files are handled first, then CSS and then JS. This is significant to know in that it will affect the placement of one's coding within various files.

**How can you find images to add to a Website?**  
There are multiple ways to find images to add to a website. Best is to create your own images so as to hold copyright. To find images to add to a website, if you are not creating your own, scan graphic repositories that offer open source materials. Unsplash is one collection that offers opensource and for-purchase images. A new tool that I learned of from this reading is the "Tool" and "Open Source" option in Google Image search.

**How do you create a String vs a Number in JavaScript?**

- To create a String in JavaScript, place single quotes around your content.
- To create a Number in JavaScript, simply place your number.

**What is a Variable and why are they important in JavaScript?**  
As per the text, "a variable is a container that stores value." In other words, it is the symbol or representation that a developer can assign meaning to. It is significant in JavaScript because, as my kiddo puts it, "a variable is a thing that can change." Meanings can be assigned and manipulated and then reassigned.

## Topic 2 - HTML Basics

HTML is a markup language that uses a series of elements to enclose, wrap, or mark up different parts of content to make is appear or act in a certain way. It tells the web browsers how to structure the web page.

**What is an HTML Attribute?**
An attribute is an additional instruction for an element. This will not appear in the content of a page. 

**Describe the anatomy of an HTMl Element.**
An HTML element begins with an opening tag, then contains the content, then closes with a closing tag as follows:
> Opening tag \- `<p>`  
> Content \- some word here  
> Closing tag \- `</p>`  

The full element would look as follows: `<p>some words here</p>`

**What is the difference between `<article>` and `<section>` element tags?**  

- An `<article>` creates a block of content that makes sense on its own. A single piece of funcitonality.
- A `<section>` creates a section or area within your page. It makes more sense within the context of multiple elements.

**A typical Website will include the following Elements:**
> `<!doctype>`  
> `<html></html>`   
> `<head></head>`  
> `<title></title>`  
> `<body>` `</body>`  
> and meta elements, header, main, navigation bar, footer  

**Metadata will influence Search Engine Optimization in the following ways:**

- It provides search engines with key info about the content of the file.
- It helps search engines understand details about the page's content which can shape how the page is ranked in search result.
- Different meta tags will provide different types of relevant information.

**How is the `<meta>` HTML tag used when specifying metadata?**  
The `<meta>` HTML tag is used with attributes when specifying metadata.The meta tag is a void element.

## Miscellaneous

**How to start to design a Website:**  

> Begin with a sketch. Often times this is a written sketch. Then transition to the use of an app to help with the mockup.  

**The most important question to answer when designing a Website is:**  

> What do you want to accomplish? How will your user be using the Website? What will your user need?  

**Why should you use an `<h1>` element over a `<span>` element?**  

> An `<h1>` element is preferable to a `<span>` element in instances where you would like its semantic properties to assist with better 
> SEO results and/or to be picked up by a screenreader, making your content more reader accesible. A `<span>` element has no semantic 
> value.  

**What are the benefits of using semantic tags in our HTML?**
> The benefits of using semantic tags in HTML are as mentioned above. Semantic tags have useful properties that not only tell browsers how to display content, but give a page an extra boost with SEO recognition and accessabiilty.  

**Describe 2 things that require JavaScript in the Browser?**  
Browser APIs can be built into your browser or grabbed from another source. Two of these APIs that are available on your browser and accessed with the use of JavaScript are:

- DOM (Document Object Model)  
- Canvas and WebGL

**How can you add JavaScript to an HTML document?**
> You can add JavaScript either externally, internally, or inline.

## Things I Want To Know More About

- Why are CodeFellow instructors writing variable names with no caps on first word and caps on all following words?
- I'm excited to pick up more HTML, CSS, and JavaScript. I'm now curious about Python. If JavaScript is so user-friendly and can do fun things, how would folks describe Python? I hear of so many developers using Python.

## Sources Directly Quoted

- MDN Web Docs, "How the Web Works"
- MDN Web Docs, "What Will Your Website Look Like?"
- MDN Web Docs, "Getting Started With HTML"

