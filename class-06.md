# class 6

## Javascript Objects Basic

**How would you describe an object to a non-technical friend you grew up with?**
A standalone entity, with properties and type. Compare it to a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, and so on. In the same way, JavaScript objects can have properties, which define their characteristics.

**What are some advantages to creating object literals?**
Some advantages are convenience, flexibility in declaration, and less code during declaration. You can drop an object literal anywhere in your program with no previous setup.

**How do objects differ from arrays?**
Objects represent “things” with characteristics (aka properties), while arrays create and store lists of data in a single variable.

**Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**
If the object's key value is only known at runtime, then we need to use bracket notation.

**Evaluate the code below. What does the term this refer to and what is the advantage to using this?**
> const dog = {
> name: 'Spot',
> age: 2,
> color: 'white with black spots',
> humanAge: function (){
> console.log(`${this.name} is ${this.age*7} in human years`);
> }
>}

This, allows us to reuse functions in different execution contexts. It means, a function once defined can be invoked for different objects using the this keyword.
