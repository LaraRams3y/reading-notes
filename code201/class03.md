# Class 03 Reading Notes

Reading for class three has been a little bit of recap of HTML, CSS, and JavaScript, and a lot of introduction to additional more complex content. I suspect that we will be applying theses concepts to our About Me pages.

### Learn HTML

**When should you use an unordered list in your HTML document?**

When it isn't significant that the information be set out or described in a particular order.

**How do you change the bullet style of unordered list items?**

The command "type" is the element that will help you change your bullets. Following "type", you can designate "circle, disk, "square", and maybe event "triangle".

**When should you use an ordered list vs an unorder list in your HTML document?**
Use UL when there is no need for numeric or specific order to a list. Use OL when you need a specific order to a list of items such as in an outline, a recipe, or an instructional excerpt.

**Describe two ways you can change the numbers on list items provided by an ordered list?**

1. One way to change the numbers on list items is to use the command "start". This will allow you to begin yor list at whichever number you would like.
2. Another way to adjust numbered lists in HTML is to indicate a "type". Various forms of "a" and"i" will shift your numbering type. "a" is for lowercase letters; "A" is for uppercase letters; "i" is for lowercase Roman numerals. "I" is for uppercase Roman numerals; "1" is for numbers (which is already the default). *notes taken from mdn web docs.

### Learn CSS

**Describe the CSS properties of margin and padding as characters in a story.**

Once upon a time there were two piggish piggies. The first piggy's name was Margin; the second piggy's name was Padding. They both liked to take up and lay claim to space.

**What is their role in a story titled: “The Box Model”?**
In the story of The Box Model castle, the piggies showed up one day to claim some space. Margin claimed the space just around the outside of Box Model castle. Padding claimed space just around the inside parameter of the castle. There were some other piggies that came to claim other spaces, but that's another story.

**List and describe the four parts of an HTML elements box as referred to by the box model.**

The four parts of an HTML elements box are content box, paddng box, border box, and margin box:

- The content box is the portion of the element box that will hold content.
- The padding box is the portion around the content that will provide space between the content and the border.
- The border box is the line around the content and padding.
- The margin is the box that provides space around the border and between any other containers.

### Learn JS

**What data types can you store inside of an Array?**
 Things and numbers. According to MDN Web Docs: We an array can store "strings, numbers, objects, and even other arrays. We can also mix data types in a single array...."

**Is the people array a valid JavaScript array?** Yes

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

**If so, how can I access the values stored?**

As per my reading in MDN Web Docs and a conversation with ChatGPT, for example, to access the 1st value stored in this array, I would type this code to create a value: const peteInfo = people[0];

Then I would type this code to access info in that value: console.log people([peteInfo]);

**List five shorthand operators for assignment in javascript and describe what they do.**

1) This is an addition assignment: x += f()
This translates to mean the operand x should be assigned the value of operand x plus operand f(). In long form it looks like this: x = x + f()

2) This is a subtraction assignment: x -= f()
This translates to mean the operand x should be assigned the value of operand x minus operand f(). In long form it looks like this: x = x - f()

3) This is a division assignment: x /= f()
This translates to mean the operand x should be assigned the value of operand x divided by operand f(). In long form it looks like this: x = x / f()

4) This is a logical OR assignment: x ||= f().
It evaluates the operand to the right and assigns to the left if the left operand is falsy. I look forward to seeing and trying this in action to get a better grasp of it. The long form expression looks like this: x || (x = f())

5) This is a left shift assignment: x <<= f(). I don't quite understand it yet. According to MDN Web Docs: "The left shift assignment (<<=) operator performs left shift on the two operands and assigns the result to the left operand." I tried to clarify my understanding of this by following links provided by MDN Web Docs. BigInt values were discussed. I look forward to understanding this content more clearly. The long form expression looks like this: x = x << f()

**Read the code below and evaluate the last expression and explain what the result would be and why.**

 >let a = 10;<br>
 >let b = 'dog';<br>
 >let c = false;<br>
 >// evaluate this<br>
 >(a + c) + b;

I originally thought that this expression would evaluate to false. I came to this conclusion based on short-circuit evaluation. My thinking was that a+c or 10+false would evaluate to false, then the next step would be false+b or false+dog, which would evaluate to false. Then I checked my thinking with ChatGPT. I discovered that I was on the wrong track. Rather than short-circuit evaluation, I needed to be applying type coercion. As per Chat GPT, with type coercion, in 10+false, false is converted to 0. Thus 10+0 is 10. Then with 10+dog, 10 will be converted to string type data and return '10dog'. This was a great exercise, as I did not get coercion in the reading, but through this activity I understand it a little more.

**Describe a real world example of when a conditional statement should be used in a JavaScript program.** In the ternary discussion, a sample conditional code served the function of differentiating between a person older than 18 or younger than 18. This would be useful in a program seeking to lock out users under the age of 18.<br><br>Another example would be when requesting a passcode of users. A conditional code will allow for a user to have another try at entering the correct passcode if the incorrect passcode was first entered.

**Give an example of when a Loop is useful in JavaScript.**
A loop is helpful for making repeat tasks automatic. I suspect that a loop could be useful in a program where a business needed to send out multiple automated monthly reminders to clientele. Or where the business needed to automate a monthly charge to a list of hundreds or thousands of subscribers.
