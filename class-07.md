# class

## Domain modeling

**Explain why we need domain modeling.**
We need to identify the key concepts in a particular domain, then clearly articulate how those concepts relate in a consistent and predictable way

## HTML Table Basics

**Why should tables not be used for page layouts?**
HTML tables were originally intended to be used for presenting tabular data, not for layout.

**List and describe 3 different semantic HTML elements used in an HTML < table >.**
th element, or table header, and td, which denotes a header. You also use tbody, or table body.

## Introducing Constructors

**What is a constructor and what are some advantages to using it?**
A constructor is a special function that creates and initializes an object instance of a class. It gets called when an object is created using the new keyword. The purpose of a constructor is to create a new object and set values for any existing object properties. Some advantages to using it are that it initializes the object with the default or initial state. It also informs about dependencies. We can find out what it needs in order to use this class, just by looking at the constructor.

**How does the term this differ when used in an object literal versus when used in a constructor?**
Objects created using object literal are singletons, this means when a change is made to the object, it affects the objects entire script. Whereas if an object is created using a constructor function and a change is made to it, that change won't affect the object throughout the script.

## Object Prototypes Using A Constructor

**Explain prototypes and inheritance via an analogy from your previous work experience. NOTE: This is a very common front end developer interview question.**
An object can inherit properties of another object. The object from where the properties are inherited is called the prototype. In short, objects can inherit properties from other objects — the prototypes.
At my last job, I would stand for the object whereas my previous work experience represents the prototype. I benefited and walked away with knowledge and many skills from my previous work experience, exactly how objects can inherit others objects, which are know as prototypes.
