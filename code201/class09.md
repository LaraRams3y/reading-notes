# How To Structure A Web Form

## HTML - Forms

**Why are forms so important in web development?**
Forms are a main point of interaction between those using websites/applications and those providing services/products/etc via the sites. A good form provides seemless service to clients and provides seemless data collection to service providers.

**When designing a form, what are some key things to keep in mind when it comes to user experience?**
Readability, usability. Keep it simple and focused. Longer, convoluted or difficult forms lose people more easily. Only ask for what is absolutely needed. Make a mockup first.

**List 5 form elements and explain their importance.**

- `<form>` -- this is a container element that designates this section or area or block will be a form. It has attributes that configure how it will behave. Typically, we should always engage the `action` and `method` attributes.
- `<label>` -- Defines a section or line within a form. Indicates what that line will intake.
- `<input>` -- The space corresponding with the label that takes in the single-line of info. Is a void element. It does not take a closing tag.
- `<textarea>` -- A space corresponding to a label which would allow multiple lines of user input, such as for comment or explanation.
- `<button>` -- allows user to send or submit their data

## JS - Introduction To Events

**How would you describe events to a non-technical friend?**

An "event" in web development tech world is when a website user does something in the website that is of note. For instance, they click on a button or complete a task that the designer is aiming to get them to do.

**When using the addEventListener() method, what 2 arguments will you need to provide?**

1. The event type: a string representing they type of event desired. For instance '"click"', '"mouseover"', etc.
2. The even handler function: the function that will be executed when the event type occurs.

**Describe the event object. Why is the target within the event object useful?**

The event object is an object automatically created when an event occurs. The target within the event object is useful because it contains information specific to that event.

**What is the difference between event bubbling and event capturing?**
Two phases of event propagation. In the capturing phase, it goes from the outer parent element and travels down to the target element.In the bubbling phase, it start from the target element and bubbles through its ancestorsin the DOM hierarchy.
