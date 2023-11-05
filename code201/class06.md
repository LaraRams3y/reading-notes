# Class 06 - JavaScript Object Basics and The DOM #

### JavaScript Object Basics ###

**How would you describe an object to a non-technical friend you grew up with?**

An object is a grouping of related variables and functions (which are called properties and methods when they are inside objects).

**What are some advantages to creating object literals?**
An Object Literal is literally written out object contents. Use an object literal when you want to transfer a series of structured, related data items in one chunk. Doing this is much more efficient than sending items individually.

**How do objects differ from arrays?**

An object is a collection of variabble and functions, while an array is a collection of bits of data. An analogy that comes to mind is that an object is the candy machine, with all the parts that make it work, while an array would be more similar to all the little bits of candy that one might be able to get out of a candy machine.

**Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**

While dot notation is best, there will be sometimes when using brackets is better. In the instance discussed by MDN Web Docs, "if an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation."

**Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?**

In the sample code, `this` refers to the variables that the methods point to: `this.name` refers to the dog "Spot" and `this.age` refers to the age of 2. `this` enables you to use the same method definition for every object you create.

### The DOM ###

**What is the DOM?**
According to MDN Web Docs, "The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page."

**Briefly describe the relationship between the DOM and JavaScript**

According to MDN Web Docs, "The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript."
