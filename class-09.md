# class 9

## HTML Forms

**Why are forms so important in web development?**
Web forms are a very powerful tool for interacting with users — most commonly they are used for collecting data from users, or allowing them to control a user interface

**When designing a form, what are some key things to keep in mind when it comes to user experience?**
Be simple and straightforward, use one column, and arrange your form fields from easiest to hardest. You also want to clearly title your form, don't ask for phone numbers and use auto-fill browsers

**List 5 form elements and explain their importance.**
The input element can be displayed in several ways and is one of the most used form elements. The label elemnt defines a label for several form elements. The select element defines a drop-down list. Textarea defines a multi-line input field (a text area). The button element defines a clickable button.

## Learn JS- Introduction To Events

**How would you describe events to a non-technical friend?**
Events are things that happen in the system you are programming, which the system tells you about so your code can react to them.

**When using the addEventListener() method, what 2 arguments will you need to provide?**
the string and a function

**Describe the event object. Why is the target within the event object useful?**
When the event occurs and it calls its associated function, it also passes a single argument to the function, a reference to the event object. The event object contains a number of properties that describe the event that occurred. The target within the event object is a property that refers to the element that triggered the event. This can be useful for identifying which element an event originated from, which is often necessary when working with event listeners. console.

**What is the difference between event bubbling and event capturing?**
In even capturing, the event moves down towards the element. In the event bubbling, the event bubbles up from the element.
