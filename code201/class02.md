# Class 02 Reading Notes

Reading for class two has been a recap of HTML, CSS, and JavaScript. However, it has also pushed us a little beyond what we encountered in Coding 102. I'm both excited and nervous to try and apply the basics that I still feel a bit shaky on in addition to advancing beyond what I've already gained.

### HTML Fundamentals & Advanced Formatting

**Why is it important to use semantic elements in our HTML?**

It is important to use semantic elements in our HTML because these elements tell browsers how to display content. As well, semantic elements provide additional content and key words for SEOs and screenreaders to pick up. What SEOs pick up will help boost the site's discoverability, and what the screenreader picks up will make the site more accesable.  

**How many levels of headings are there in HTML?**

!! 6 !! There are SIX levels of headings! Here are some key points about headings to remember!

- Use only one `<h1>` heading per page.
- Use headings in order. It will look a little weird if you start your page with an `<h6>`, then plop in an `<h1>` a little further on.
- No more than three different heading styles per page, for the sake of your user's sanity.

**What are some uses for the `<sup>` and `<sub>` elements?**  

>`<sup>` = This creates superscript, like when you want to add a suffix to a number  
>`<sub>` = This creates subscript, like when you want to creat subscript numbers for an element from the periodic table.  

**When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?**  
To provide the full expansion of an acronym, use the title attribute as follows:
>`<p>`  
> I work at `<abbr title="South Puget Sound Community College">`SPSCC.`</abbr>`  
>`</p>`

### CSS Structure

**Ways we can apply CSS to our HTML:**

- as a separate file or external stylesheet
- as an inline style sheet
- or in-file or internal stylesheet

**We should avoid using inline styles:** Because it is the least efficient approach, most often creating more work than is necessary in constructing and maintaining a site. Inline style leads to challenging code situations.

**The following image reviews these CSS terms: "selector", "properties", "declaration":**

![Image of sample code for a level-two header with declarations for black text and 5px padding. The following terms have been written in in pink: "selector", "properties", and "declaration". Arrows draw the terms to their corresponding code.](/graphics/codereview.png)

### JavaScript Review

**A sequence of text enclosed in single quote marks is a:** string

**Four types of JavaScript operators are:**

- "Assignment" is represented with an equal sign (=); it is best not to think "equal" but rather "assigned"
- "Strict Equality" is represented by a line of three consecutive equal symbols (===)
- "Not" is represented by an exclamation mark (!)
- "Addition" is represented by a plus sign (+)

**Two real world problems one could solve with a Function:** mathematical equations and data analysis

### The following notes pertain to JavaScript Conditionals

**If Statements**
An if statement checks a CONDITION and if it evaluates to TRUE, then the code block will execute.

**What is the use of an else if?**
An else if gives the possibility of additional options of  the condition evaluates to false.

**Three different types of comparison operators:**

- `<` this operator describes less than
- `<=` This operator describes less than or equal to
- `>` This operator describes greater than

**What is the difference between the logical operator && and `||`?**

- |The logical operator && equates to AND. It initiates a check to see if BOTH operands are true. It asks "Are both operand 1 AND operand 2 true? They must both be true for this logical operator to evaluate to true.
- |The logical operator `||` equates to OR. It initiates a check to see if one or the other operand is true. It asks "Is operand 1 OR operand 2 true? If at least one of the operands evaluates to true, then the logical operator evaluates to true.

### Things I Want to Know More About

The text got pretty intense there with the JavaScript operands, logical operators and functions. I am looking forward to moving from complete mystery to clarity on it all.

### Additional Sources Consulted

I have been enjoying chatting with ChatGPT. It helped me come up with my second point for real world problems JavaScript can solve. It also helped me recall markdown syntax for inserting an image and for inserting an emoji. It has not been able to tell me why my spouse was upset after having to stop at three different grocery stores to get the best prices on paneer cheese. It also failed to tell me why my kiddo thinks he's the boss and can tell my partner and I how to manage the household.