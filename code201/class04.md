# Class 04 Reading Notes

### HTML

1. To create a basic link, we wrap text or other content inside what element? To create a basic link, wrap the designated content inside an anchor element: <a></a>

2. The `href` attribute contains what information? The hypertext reference attribute contains a web address.

3. What are some ways we can ensure links on our pages are accessible to all readers? Make sure the link text itself is accuarate and clear in its description of what it links to so as to stand on its own, out of context. This helps people who use screen readers and jump from link to link in a web page. This also helps search engines more concisely index these target files. It is also useful for readers who skim the page and whose eyes land on features that stand out, such as links.

**Additional tips are:**

1. Don't use the URL as the text part of the link. 
2. There's no need to state "link" in a link. Screen readers already say this and visual readers already know this.
3. It's best to keep your link text short.
4. It's best to create link text that is unique and clearly descriptive. "Click Here" is an example of something that is not unique and is not clearly descriptive. "Click Here" tells us nothing about the link.
5. Add clear wording to links that will download a resource so users know what to expect. Include in a parenthetical aside the type of download resource, where it will load to, how much memory it will take, etc.
6. This is great! Use the "download" attribute to give the downloadable file a default save-file-name.

### CSS

**What is meant by “normal flow”?**

>Normal flow is the standard way a webpage accepts >items for layout. When a designer applies CSS, >this will adjust that "normal flow".

**What are a few differences between block-level and inline elements?** 

>Block-level elements are layed out on top of each >other. They build out vertically and stacked. >Inline elements build out side by side on the same >line as long as there is space for them. 
<br>
>_Block-level__ positioning is the default for >every html element.

**Name a few advantages to using absolute positioning on an element.**

> A few advantages to using absolute positioning are one, that it no longer exists in the normal >document flow. It can support the creation of >elements that don't interfere with the layout of >other elements on the page. For instance, I can >create a logo in absolute and place it over the >nav bar with my buttons centered and flexed, and >the logo won't reposition or bother them... >something I was trying to figure out in lab 02. >Other items that absolute positioning can >accomodate are popup information boxes, control >menus and rollover panels.

**What is a key difference between fixed positioning and absolute positioning?** 

> According to mdn web docs, "whereas absolute positioning fixes an element in place relative to its nearest positioned ancester... fixed positioning usually fixes an element in place relative to the visible portion of the viewport.

### JS: Functions – Reusable Blocks of Code

**Describe the difference between a function declaration and a function invocation.**

A function declaration is the code that creates a function. A function invocation is the code that calls on the created function to complete the task for which it was created.

**What is the difference between a parameter and an argument?**

The parameter is the parenthesis when a function is called; the argument are the values or the stuff inside the parenthesis when a function is called. There may or may not be something inside the parenthesis. According to chatGPT, "...parameters are placeholders in a function's definition, while arguments are the actual values or expressions passed to the function when it's called to fulfill the parameter requirements. Parameters define what data a function should expect, and arguments provide that data."

### Miscellaneous

**Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.**

1. Greater Efficiency - I'm going to focus in on the last points mentioned in this section: "Researches also identified pairing enhances technical skills, team communication, and even enjoyability of coding in the workplace." I like that this section mentions team building items. I am intimidated by the thought of team coding as it can be perceived as a vulnerable space where someone will see my lack of skill and knowledge. If I approach this with ideas of team building and enjoyability, I think that will get me past the initial hesitation. I deeply value team building, community, joy in connecting with others. How great to be able to achieve greater efficiency at the same time we're achieving community.

2. Learning From Fellow Students - My current work is very individualistic. The instances where I learned from fellow students or colleagues have been accidental and far and few between. This sounds like a welcome change, to be in it with others rather than carrying it all on my own. Although, I think this is also just a hallmark of this industry.
